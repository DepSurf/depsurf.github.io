# Function: <code>iowrite16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049648,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:116",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049648,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343712,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:116",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343712,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469088,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:116",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469088,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491328,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:116",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491328,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672368,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:117",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672368,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890144,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:117",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890144,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974384,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:117",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974384,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156656,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156656,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290400,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290400,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584701360,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701360,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814656,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814656,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859216,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859216,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585280672,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280672,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586132160,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132160,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123136,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:209",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite16le",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123136,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385344,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:209",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite16le",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385344,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719696,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:209",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_size",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_enable",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite16le",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719696,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
  "name": "iowrite16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496643232,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498181244,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498185704,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498188340,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500098424,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_check_media",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_write",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_write",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_write",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_read",
        "drivers/net/ethernet/smsc/smc91x.c:smc_mii_out",
        "drivers/net/ethernet/smsc/smc91x.c:smc_mii_out",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_tx",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501526328,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501574940,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_write16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501580788,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_interrupt",
        "drivers/clocksource/sh_tmu.c:sh_tmu_interrupt",
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_disable",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_enable"
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
  "name": "iowrite16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229860396,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/pinctrl/pinctrl-rza1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_set",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3229955672,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243763820,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/clk/renesas/clk-rz.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230944772,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3230950188,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952628,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 3231773304,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/mfd/asic3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/asic3.c:asic3_remove",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_mmc_enable",
        "drivers/mfd/asic3.c:asic3_clk_disable",
        "drivers/mfd/asic3.c:asic3_clk_enable",
        "drivers/mfd/asic3.c:asic3_gpio_set",
        "drivers/mfd/asic3.c:asic3_gpio_direction",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_unmask_irq",
        "drivers/mfd/asic3.c:asic3_unmask_gpio_irq",
        "drivers/mfd/asic3.c:asic3_mask_irq",
        "drivers/mfd/asic3.c:asic3_mask_gpio_irq",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_set_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3231792564,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/mfd/tc6393xb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_lcd_mode",
        "drivers/mfd/tc6393xb.c:tc6393xb_lcd_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 3232406716,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/mtd/nand/raw/omap2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf16"
      ],
      "caller_func": []
    },
    {
      "addr": 3234043752,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db"
      ],
      "caller_func": []
    },
    {
      "addr": 3234087376,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_write16"
      ],
      "caller_func": []
    },
    {
      "addr": 3234092160,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/clocksource/sh_mtu2.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234094612,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_interrupt",
        "drivers/clocksource/sh_tmu.c:sh_tmu_interrupt",
        "drivers/clocksource/sh_tmu.c:sh_tmu_set_next",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_disable",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_enable"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290443360,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290443360,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "iowrite16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275961160,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275966552,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275969180,
      "name": "iowrite16",
      "external": false,
      "loc": "include/asm-generic/io.h:728",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259136,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259136,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194336,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194336,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242896,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242896,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void iowrite16(u16 val, void * addr)
```

```json
{
  "name": "iowrite16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347728,
      "name": "iowrite16",
      "external": true,
      "loc": "lib/iomap.c:193",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:del_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:vp_config_vector",
        "drivers/virtio/virtio_pci_modern.c:vp_set",
        "drivers/virtio/virtio_pci_common.c:vp_notify",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:del_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:vp_config_vector",
        "drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347728,
      "name": "iowrite16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void iowrite16(u16 val, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iowrite16(u16 val, void * addr)
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
void iowrite16(u16 val, void * addr)
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
