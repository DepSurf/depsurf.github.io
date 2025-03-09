# Function: <code>pci_irq_get_affinity</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583834416,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1299",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583834416,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583876736,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1243",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876736,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584140208,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1243",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140208,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584356896,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1242",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584356896,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584451808,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1262",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451808,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584648592,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1291",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584648592,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584786224,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786224,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585477056,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585477056,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585517296,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1312",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517296,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585395856,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1318",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395856,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585859424,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1238",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859424,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052928,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:1094",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052928,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588235136,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi/api.c:342",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588235136,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588510640,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi/api.c:342",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588510640,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588809232,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi/api.c:342",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-pci.c:blk_mq_pci_map_queues",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809232,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497052856,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497052856,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230263444,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230263444,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291090384,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291090384,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275699684,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275699684,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584734976,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734976,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584665744,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665744,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584736384,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736384,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```

```json
{
  "name": "pci_irq_get_affinity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584843952,
      "name": "pci_irq_get_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1292",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_irq_get_node",
        "drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843952,
      "name": "pci_irq_get_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
const struct cpumask * pci_irq_get_affinity(struct pci_dev * dev, int nr)
```
</details>
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
