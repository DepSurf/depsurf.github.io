# Function: <code>modalias_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583282448,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:157",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583414208,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:91",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583820512,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:35",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583887216,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:401",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584408560,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:810",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584709264,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:254",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585031504,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:57",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585235312,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:943",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585544752,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:366",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585966240,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:49",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282448,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583414208,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071583820512,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071583887216,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584408560,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584709264,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585031504,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585235312,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585544752,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071585966240,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583593360,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:157",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583734096,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:91",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584147440,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:35",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584217968,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:401",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584743920,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:830",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585057680,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:517",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585416144,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:57",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585628736,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:966",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585938480,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:366",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586371664,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:49",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593360,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583734096,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071584147440,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071584217968,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584743920,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585057680,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585416144,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585628736,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585938480,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586371664,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583730496,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:158",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583873632,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:91",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584328016,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:35",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584399392,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:401",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584933936,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:844",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585241472,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:519",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585617056,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:58",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585816352,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:983",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586126832,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:366",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586580496,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:49",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730496,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583873632,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071584328016,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071584399392,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584933936,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585241472,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585617056,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585816352,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071586126832,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586580496,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583772928,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:280",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583924080,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:91",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584407952,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:35",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584481904,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585018560,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:844",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585323392,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:582",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585700832,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585903232,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:983",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586215136,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:366",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586705248,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:50",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583772928,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071583924080,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584407952,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071584481904,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585018560,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585323392,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585700832,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585903232,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071586215136,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071586705248,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584032784,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:281",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584186704,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:91",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584815232,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:35",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584892176,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585175632,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:281",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585440880,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:844",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585751360,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:582",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586133152,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:64",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586344000,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:984",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586678464,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:366",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587190016,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:50",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584032784,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584186704,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071584815232,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071584892176,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585175632,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585440880,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585751360,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586133152,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586344000,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071586678464,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587190016,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584230176,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:264",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584407008,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:91",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585045680,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:35",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585123232,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585411280,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:22",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585683936,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:842",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585997360,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:590",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586381584,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:67",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586601632,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1006",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586944032,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:366",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587490272,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:50",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230176,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584407008,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585045680,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585123232,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585411280,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585683936,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585997360,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586381584,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586601632,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071586944032,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587490272,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584319840,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:263",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584502336,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:91",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585153472,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:35",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585234048,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585534736,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585814080,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:844",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586134720,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:619",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586522880,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:57",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586750480,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1009",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587104816,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:362",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587670416,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:50",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319840,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584502336,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585153472,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585234048,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585534736,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585814080,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586134720,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586522880,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586750480,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071587104816,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587670416,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584514896,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584699856,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585360864,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585446208,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585754448,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586047440,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:884",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586368976,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:650",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586446432,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586767360,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587005552,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587369216,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587948720,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584514896,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584699856,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585360864,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585446208,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585754448,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586047440,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071586368976,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586446432,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586767360,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071587005552,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071587369216,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587948720,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584650800,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584835664,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585499456,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585586640,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585896672,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586195536,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586518624,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:648",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586594368,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586913808,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587205040,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587571056,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588154640,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584650800,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584835664,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585499456,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585586640,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585896672,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586195536,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071586518624,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586594368,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586913808,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071587205040,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071587571056,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071588154640,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585334560,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:249",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585529840,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586222416,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586307968,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:398",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586634864,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:26",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586956176,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:1012",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587299120,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:653",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587380368,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587724192,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588057392,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1135",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588430880,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588546992,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:477",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589019152,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334560,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071585529840,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586222416,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586307968,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586634864,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586956176,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071587299120,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587380368,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587724192,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588057392,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071588430880,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071588546992,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071589019152,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585487760,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:258",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585665712,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586341120,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586426608,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:399",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586743888,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:26",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587041232,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:1267",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587360368,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:650",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587441280,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1195",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587783856,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588102784,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1135",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588463056,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588572544,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:605",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589028592,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487760,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585665712,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586341120,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586426608,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586743888,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587041232,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587360368,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587441280,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587783856,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588102784,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071588463056,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071588572544,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071589028592,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585368144,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:258",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585546496,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585682416,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/acpi/device_sysfs.c:329",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586225424,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586310608,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:465",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586627488,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:26",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586925040,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:1266",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587242384,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:645",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587323072,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1196",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587663136,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:56",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587985488,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1138",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588345552,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588456064,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:649",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588915872,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585368144,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071585546496,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585682416,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586225424,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586310608,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586627488,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586925040,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587242384,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587323072,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587663136,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071587985488,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071588345552,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071588456064,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071588915872,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585827712,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:258",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586017248,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586162352,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/acpi/device_sysfs.c:334",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586731888,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:37",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586830208,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:462",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587174112,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:26",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587487280,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:1230",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587808848,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:639",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587889920,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1194",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588251680,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:56",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588598496,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1114",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589004496,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589124128,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:650",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589455760,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:174",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589622752,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827712,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586017248,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586162352,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586731888,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586830208,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587174112,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587487280,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587808848,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587889920,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588251680,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071588598496,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071589004496,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071589124128,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071589455760,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589622752,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587018912,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:279",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587236224,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587396336,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/acpi/device_sysfs.c:335",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588005104,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:38",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588114112,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:463",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588486464,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:26",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588809728,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:1239",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589157584,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:627",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589239024,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1224",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589635584,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:56",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590010976,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1114",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590441504,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590574624,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:651",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590932320,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:174",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591121536,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:47",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018912,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071587236224,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587396336,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071588005104,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071588114112,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071588486464,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071588809728,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071589157584,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071589239024,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071589635584,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071590010976,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071590441504,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071590574624,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071590932320,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071591121536,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588188384,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:280",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588470528,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588649712,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/acpi/device_sysfs.c:335",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589376304,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:38",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589500160,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:463",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589922608,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:26",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590307680,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:1239",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590708832,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:640",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590797968,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1224",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236512,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:58",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591611696,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1110",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592080864,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:347",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592230752,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:652",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592633360,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:174",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592843696,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:47",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188384,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071588470528,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071588649712,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071589376304,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071589500160,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071589922608,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071590307680,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071590708832,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590797968,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071591236512,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071591611696,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071592080864,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071592230752,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071592633360,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071592843696,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588464368,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:280",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588749712,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588937552,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/acpi/device_sysfs.c:335",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589674944,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:38",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589800960,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:463",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590231872,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:26",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590628128,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:1243",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591050032,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:640",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591139488,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1254",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591596048,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:58",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592033936,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1110",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592503584,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:347",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592655136,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:667",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593064000,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:174",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593280336,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:47",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464368,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071588749712,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071588937552,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071589674944,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071589800960,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071590231872,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071590628128,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071591050032,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591139488,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071591596048,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071592033936,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071592503584,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071592655136,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071593064000,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071593280336,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588761472,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:279",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589052928,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589234112,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/acpi/device_sysfs.c:333",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590005824,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:38",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590137184,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:463",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590572576,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:28",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590987344,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:1243",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591394592,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:640",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591485184,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:1255",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592327760,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:58",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592773968,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1107",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593248080,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:347",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593400288,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:670",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593815888,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:174",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594036272,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:47",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761472,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071589052928,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071589234112,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071590005824,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071590137184,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071590572576,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071590987344,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071591394592,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591485184,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071592327760,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071592773968,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071593248080,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071593400288,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071593815888,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071594036272,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496448592,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/bus/fsl-mc/fsl-mc-bus.c:140",
      "file": "drivers/bus/fsl-mc/fsl-mc-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496897568,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497229704,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498154784,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498252104,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498715936,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498995664,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499402320,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:648",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499478384,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499864112,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500289744,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500715456,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501407400,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496448592,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336496897568,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446603336497229704,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336498154784,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336498252104,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336498715936,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446603336498995664,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446603336499402320,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336499478384,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336499864112,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446603336500289744,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336500715456,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336501407400,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230175024,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230415744,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230919620,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231342264,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231563564,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231951668,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232427660,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232759160,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233242740,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233896832,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230175024,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3230415744,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 3230919620,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3231342264,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3231563564,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 3231951668,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3232427660,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3232759160,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3233242740,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 3233896832,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283211936,
      "name": "modalias_show",
      "external": false,
      "loc": "arch/powerpc/platforms/pseries/vio.c:1542",
      "file": "arch/powerpc/platforms/pseries/vio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290987664,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291177504,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291381712,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291866480,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292153216,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292641248,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:648",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292757872,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293195648,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293593632,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294150224,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294974768,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283211936,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 13835058055290987664,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 13835058055291177504,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055291381712,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 13835058055291866480,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055292153216,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 13835058055292641248,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055292757872,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055293195648,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 13835058055293593632,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 13835058055294150224,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055294974768,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275589426,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275768682,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275938710,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276229506,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276370196,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276633796,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:648",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276697090,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276978480,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277199334,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277564786,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278014090,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275589426,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446743936276229506,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446743936276370196,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446743936276633796,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446743936276697090,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446743936276978480,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446743936277564786,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446743936275768682,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446743936275938710,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446743936277199334,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446743936278014090,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584601280,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584787136,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585261536,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585348576,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:398",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585657664,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585955744,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586209104,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:648",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586284848,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586670832,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586911120,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587264080,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587776208,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601280,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584787136,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585261536,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585348576,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585657664,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585955744,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071586209104,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586284848,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586670832,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586911120,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071587264080,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587776208,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584531088,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584717920,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585214160,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585804960,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586027472,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:648",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586122336,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586539168,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586852288,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587032416,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587550192,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/hv/vmbus_drv.c:192",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531088,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584717920,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585214160,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585804960,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071586027472,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586122336,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586539168,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586852288,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071587032416,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587550192,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584600960,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584788560,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585449856,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585537040,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585847072,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586145552,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586466592,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:648",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586542336,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586868368,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587159600,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587522304,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588109168,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600960,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584788560,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585449856,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585537040,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585847072,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586145552,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071586466592,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586542336,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586868368,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071587159600,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071587522304,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071588109168,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t modalias_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "modalias_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584708656,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/pci/pci-sysfs.c:266",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584893408,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/rapidio/rio-sysfs.c:87",
      "file": "drivers/rapidio/rio-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585558048,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/virtio/virtio.c:36",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585645024,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_probe.c:397",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585954688,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/tty/serdev/core.c:25",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586254256,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/base/platform.c:949",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586578272,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:648",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586654112,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/dax/bus.c:314",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586974480,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/spi/spi.c:60",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587266672,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/usb/core/sysfs.c:1130",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587634448,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:350",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588226704,
      "name": "modalias_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio_bus.c:46",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708656,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584893408,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585558048,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585645024,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585954688,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586254256,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071586578272,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586654112,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586974480,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071587266672,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071587634448,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071588226704,
      "name": "modalias_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
