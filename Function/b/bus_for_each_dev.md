# Function: <code>bus_for_each_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389328,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:301",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389328,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584724256,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:300",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724256,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584914048,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:300",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914048,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999376,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:300",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999376,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585421296,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:300",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421296,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664080,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:298",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664080,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585793744,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:301",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793744,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027008,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027008,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174464,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174464,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586936062,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:292",
      "file": "drivers/base/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_rescan_devices"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934416,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587021342,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:292",
      "file": "drivers/base/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_rescan_devices"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587019712,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586904974,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:292",
      "file": "drivers/base/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_rescan_devices"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_port",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586903344,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587466830,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:288",
      "file": "drivers/base/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_rescan_devices"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_port",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587465104,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588787117,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:288",
      "file": "drivers/base/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_rescan_devices"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_for_each_dev",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785152,
      "name": "bus_for_each_dev",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590282285,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:288",
      "file": "drivers/base/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_rescan_devices"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_for_each_dev",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_device_unregister",
        "drivers/iommu/iommu.c:iommu_device_unregister",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/usb/core/driver.c:usb_register_device_driver",
        "drivers/i2c/i2c-core-base.c:i2c_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590280032,
      "name": "bus_for_each_dev",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_for_each_dev(const struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590604159,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:354",
      "file": "drivers/base/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_rescan_devices"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_for_each_dev",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_device_unregister",
        "drivers/iommu/iommu.c:iommu_device_unregister",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/base/soc.c:soc_device_match",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/usb/core/driver.c:usb_register_device_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590601488,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_for_each_dev(const struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590963103,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:354",
      "file": "drivers/base/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_rescan_devices"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_for_each_dev",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:iommu_domain_alloc",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_device_unregister",
        "drivers/iommu/iommu.c:iommu_device_unregister",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/platform.c:__platform_driver_probe",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/base/soc.c:soc_device_match",
        "drivers/spi/spi.c:__spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/usb/core/driver.c:usb_register_device_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590960432,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498971176,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/amba/bus.c:amba_find_device",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev",
        "drivers/firmware/arm_scmi/bus.c:scmi_bus_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498971176,
      "name": "bus_for_each_dev",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231540804,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/omap_device.c:__omap_device_late_init",
        "drivers/amba/bus.c:amba_find_device",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev",
        "drivers/firmware/arm_scmi/bus.c:scmi_bus_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231540804,
      "name": "bus_for_each_dev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292118336,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292118336,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276350256,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276350256,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585934832,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585934832,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585783968,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585783968,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586124480,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586124480,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int bus_for_each_dev(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "bus_for_each_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233088,
      "name": "bus_for_each_dev",
      "external": true,
      "loc": "drivers/base/bus.c:291",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/iommu/iommu.c:bus_set_iommu",
        "drivers/base/bus.c:bus_rescan_devices",
        "drivers/base/dd.c:driver_attach",
        "drivers/base/memory.c:for_each_memory_block",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/usb.c:usb_for_each_dev",
        "drivers/i2c/i2c-core-base.c:i2c_for_each_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233088,
      "name": "bus_for_each_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type * bus</code> ➡️ <code>const struct bus_type * bus</code>
</li>
</ul>
</details>
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
