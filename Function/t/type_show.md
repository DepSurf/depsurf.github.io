# Function: <code>type_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579060880,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:116",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580390336,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:7515",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583478720,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:199",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583907424,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:41",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583939136,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:548",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584424912,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:270",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585239840,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:58",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585544960,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:374",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585675680,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:591",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585929280,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:31",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585989696,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:389",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586007440,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:38",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586406800,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:112",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587304960,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:620",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060880,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071580390336,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583478720,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071583907424,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583939136,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071584424912,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585239840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071585544960,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585675680,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585929280,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071585989696,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586007440,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586406800,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587304960,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579057264,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:116",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580457904,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:8521",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583799056,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:208",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584236608,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:41",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584264080,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:524",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584760688,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:270",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585633488,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:58",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585938688,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:374",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586074624,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_core.c:591",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586333808,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:31",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586396112,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:389",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586415440,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:38",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586849600,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:112",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587773696,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:616",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057264,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071580457904,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583799056,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071584236608,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584264080,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071584760688,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585633488,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071585938688,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586074624,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586333808,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071586396112,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586415440,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586849600,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587773696,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579056288,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:116",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579787216,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:187",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580520320,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:8710",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583938320,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:208",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584418048,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:41",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584445840,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:525",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584950640,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:401",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585821104,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586127040,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:374",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586286304,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:29",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586542576,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:31",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586604960,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:389",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586624752,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:34",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587040352,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:112",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587988896,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:616",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056288,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071579787216,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071580520320,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583938320,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584418048,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584445840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071584950640,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071585821104,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586127040,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586286304,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586542576,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071586604960,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586624752,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587040352,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587988896,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579048480,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:116",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579784736,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:199",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580553520,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:8921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583986256,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:213",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584501824,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:41",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584529504,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:525",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585035520,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:401",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585907984,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586215344,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:374",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586385280,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:29",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586665104,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:33",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586729920,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:389",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586748720,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:34",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587169488,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:113",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588146928,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:674",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048480,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071579784736,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071580553520,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583986256,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584501824,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584529504,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585035520,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071585907984,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586215344,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586385280,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586665104,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071586729920,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586748720,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587169488,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588146928,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579057344,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:116",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579818208,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:197",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580634240,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:8937",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584202048,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:213",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584911840,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:41",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584939664,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:525",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585458384,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:414",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586348768,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586678672,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:374",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586848272,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:29",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587149168,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:33",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587214128,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:389",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587233152,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:34",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587674832,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:114",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588695168,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:674",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057344,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071579818208,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071580634240,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584202048,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584911840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584939664,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585458384,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071586348768,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586678672,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586848272,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587149168,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071587214128,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587233152,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587674832,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588695168,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579062256,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:116",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579852064,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:197",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580760800,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9459",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584422384,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:213",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585143424,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:41",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585180224,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:595",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585701936,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:404",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586606400,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586944240,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:374",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587140352,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587448528,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:33",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587515008,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:389",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587534048,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:34",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588004416,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:114",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589061920,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:688",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062256,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071579852064,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071580760800,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584422384,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585143424,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585180224,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585701936,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071586606400,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586944240,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587140352,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587448528,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071587515008,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587534048,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588004416,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589061920,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579066832,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:116",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579899056,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:197",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580827312,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9502",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584518784,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:213",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585254256,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:41",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585281808,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:786",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585830192,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:398",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586755264,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587105024,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:370",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587320240,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587628640,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:33",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587695264,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:390",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587714896,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:34",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587783200,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:94",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588163264,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:115",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589287616,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:690",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066832,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071579899056,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071580827312,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584518784,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585254256,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585281808,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585830192,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071586755264,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071587105024,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587320240,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587628640,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071587695264,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587714896,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587783200,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071588163264,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589287616,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579075376,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:115",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579933872,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580921984,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9805",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584717584,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:214",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585463728,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585487376,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:768",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586065168,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587010752,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587369424,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587591120,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587906432,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587974480,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587993920,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588093728,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588488400,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589744048,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075376,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071579933872,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071580921984,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584717584,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585463728,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585487376,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586065168,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071587010752,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587369424,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587591120,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587906432,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071587974480,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587993920,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071588093728,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588488400,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589744048,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579077376,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:115",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579984000,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580975440,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584853680,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585604432,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585627968,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586213056,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587210240,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587571264,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587794560,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588112384,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588181616,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588201440,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588299472,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588696080,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589967760,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077376,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071579984000,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071580975440,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584853680,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585604432,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585627968,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586213056,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071587210240,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587571264,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587794560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588112384,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071588181616,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588201440,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071588299472,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588696080,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589967760,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579088400,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:120",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580032304,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581142608,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:10469",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585549680,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586327072,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586349296,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:777",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586543472,
      "name": "type_show",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:2629",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586978224,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588062752,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588431088,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588640912,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588974816,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589046992,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589067776,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589174400,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:105",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589564400,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590997792,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088400,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071580032304,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071581142608,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585549680,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071586327072,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586349296,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586543472,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586978224,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071588062752,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588431088,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588640912,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588974816,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071589046992,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589067776,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071589174400,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071589564400,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071590997792,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579090368,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:120",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579709840,
      "name": "type_show",
      "external": false,
      "loc": "kernel/reboot.c:692",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580016016,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581182560,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:10751",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585683968,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:270",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586444928,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586466976,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:800",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586654288,
      "name": "type_show",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:2636",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587064768,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:401",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588108080,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588463264,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588662960,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588986832,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589056064,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589071776,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589170992,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:189",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589572128,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:111",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591062464,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:690",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090368,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071579709840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580016016,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071581182560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585683968,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071586444928,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586466976,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586654288,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071587064768,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071588108080,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588463264,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588662960,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588986832,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071589056064,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589071776,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071589170992,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071589572128,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071591062464,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096928,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:120",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579717248,
      "name": "type_show",
      "external": false,
      "loc": "kernel/reboot.c:692",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580016560,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581200944,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:10881",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585564672,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:270",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585733904,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/dock.c:550",
      "file": "drivers/acpi/dock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586092608,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586328784,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586350656,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:801",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586538208,
      "name": "type_show",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:2633",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586948736,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:401",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587990768,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588345760,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588545712,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588873232,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588943328,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588958880,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589064832,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:189",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589470784,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:111",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590993232,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:691",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096928,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071579717248,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580016560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071581200944,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585564672,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585733904,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586092608,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586328784,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586350656,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586538208,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071586948736,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071587990768,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071588345760,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588545712,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588873232,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071588943328,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588958880,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071589064832,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071589470784,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071590993232,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579120560,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:135",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579795568,
      "name": "type_show",
      "external": false,
      "loc": "kernel/reboot.c:771",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580148784,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581441440,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:10993",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586036496,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:270",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586215968,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/dock.c:550",
      "file": "drivers/acpi/dock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586589840,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586848560,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586871008,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:791",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587076624,
      "name": "type_show",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:2648",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587513360,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:402",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588386560,
      "name": "type_show",
      "external": false,
      "loc": "drivers/net/wwan/wwan_core.c:257",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588603824,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589004704,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589219792,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589575728,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589651840,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589668336,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589782832,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:190",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590209728,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:111",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591830944,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:691",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071579795568,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580148784,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071581441440,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586036496,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586215968,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586589840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586848560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586871008,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071587076624,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071587513360,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071588386560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071588603824,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071589004704,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589219792,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071589575728,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071589651840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589668336,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071589782832,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071590209728,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071591830944,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579153120,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:135",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579903120,
      "name": "type_show",
      "external": false,
      "loc": "kernel/reboot.c:1143",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580291360,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581782368,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:10929",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587256304,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:270",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587453904,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/dock.c:549",
      "file": "drivers/acpi/dock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587850448,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588134960,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:37",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588158752,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:792",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588381696,
      "name": "type_show",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:2695",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588841296,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:402",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589783376,
      "name": "type_show",
      "external": false,
      "loc": "drivers/net/wwan/wwan_core.c:323",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590016928,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590441792,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590682736,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591070736,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:31",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591153792,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:382",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591171904,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591294016,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:195",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591783440,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:113",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593545216,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:691",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153120,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071579903120,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071580291360,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071581782368,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071587256304,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071587453904,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071587850448,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071588134960,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588158752,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071588381696,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071588841296,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071589783376,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071590016928,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071590441792,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071590682736,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071591070736,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071591153792,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071591171904,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071591294016,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071591783440,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071593545216,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579201552,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:135",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579737136,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/platform/efi/runtime-map.c:33",
      "file": "arch/x86/platform/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580055456,
      "name": "type_show",
      "external": false,
      "loc": "kernel/reboot.c:1160",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580501808,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582208560,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:11268",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588495712,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:270",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588715392,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/dock.c:549",
      "file": "drivers/acpi/dock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589193952,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589524048,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:37",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589556176,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:792",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589805568,
      "name": "type_show",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:2829",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590342704,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:454",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591434192,
      "name": "type_show",
      "external": false,
      "loc": "drivers/net/wwan/wwan_core.c:328",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591618176,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592081216,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:355",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592351968,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592785264,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:31",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592880912,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:382",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593044592,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:195",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593576192,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:113",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595466768,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:691",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201552,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071579737136,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580055456,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071580501808,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071582208560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588495712,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071588715392,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071589193952,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071589524048,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589556176,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071589805568,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071590342704,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071591434192,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071591618176,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071592081216,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071592351968,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071592785264,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071592880912,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071593044592,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071593576192,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071595466768,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579205648,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:135",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579783616,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/platform/efi/runtime-map.c:33",
      "file": "arch/x86/platform/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580109888,
      "name": "type_show",
      "external": false,
      "loc": "kernel/reboot.c:1160",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580573584,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582408560,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:11310",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588775456,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:270",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589003584,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/dock.c:549",
      "file": "drivers/acpi/dock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589488112,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589825120,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:40",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589857952,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:858",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590110352,
      "name": "type_show",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:2861",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590662880,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:656",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591849232,
      "name": "type_show",
      "external": false,
      "loc": "drivers/net/wwan/wwan_core.c:332",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592040672,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592503936,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:355",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592778576,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593221664,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:31",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593319392,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:382",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593497712,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:203",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594048336,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:113",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595973840,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:691",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205648,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071579783616,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580109888,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071580573584,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071582408560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588775456,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071589003584,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071589488112,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071589825120,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589857952,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071590110352,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071590662880,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071591849232,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071592040672,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071592503936,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071592778576,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071593221664,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071593319392,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071593497712,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071594048336,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071595973840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579234992,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:135",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579817344,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/platform/efi/runtime-map.c:33",
      "file": "arch/x86/platform/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580154928,
      "name": "type_show",
      "external": false,
      "loc": "kernel/reboot.c:1183",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580637824,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:230",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582576784,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:11380",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589078800,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:270",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589307888,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/dock.c:549",
      "file": "drivers/acpi/dock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589795056,
      "name": "type_show",
      "external": false,
      "loc": "drivers/acpi/bgrt.c:28",
      "file": "drivers/acpi/bgrt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590161792,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:40",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590195120,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:860",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590449712,
      "name": "type_show",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:2897",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591023456,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:663",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592780704,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593248432,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:355",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593527648,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593976432,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:31",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594075936,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:382",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594245072,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/core.c:177",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594837328,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:114",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596836176,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:703",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234992,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071579817344,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580154928,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071580637824,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071582576784,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071589078800,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071589307888,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071589795056,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071590161792,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590195120,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071590449712,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071591023456,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071592780704,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071593248432,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071593527648,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071593976432,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071594075936,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071594245072,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071594837328,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071596836176,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491169968,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492325056,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497241368,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498270056,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498286472,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499020128,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500296080,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500715728,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500995720,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501364840,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501486024,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501822912,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502259040,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503703112,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491169968,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446603336492325056,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446603336497241368,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446603336498270056,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336498286472,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446603336499020128,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446603336500296080,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446603336500715728,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336500995720,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336501364840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446603336501486024,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336501822912,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336502259040,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336503703112,
      "name": "type_show",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225194856,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226216608,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230426968,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230966560,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231582076,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232764712,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233242972,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233508580,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233854956,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234025892,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234341404,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235004836,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236338328,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225194856,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 3226216608,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3230426968,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3230966560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 3231582076,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 3232764712,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 3233242972,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3233508580,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3233854956,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 3234025892,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3234341404,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3235004836,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 3236338328,
      "name": "type_show",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t type_show(struct kobject * k, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282336256,
      "name": "type_show",
      "external": false,
      "loc": "arch/powerpc/kernel/cacheinfo.c:601",
      "file": "arch/powerpc/kernel/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284069488,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285570880,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291215840,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291449024,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292182688,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293602128,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294150560,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294470560,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294919328,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295223248,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295751776,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297535648,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282336256,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055284069488,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 13835058055285570880,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 13835058055291215840,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055291449024,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 13835058055292182688,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 13835058055293602128,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 13835058055294150560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 13835058055294470560,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055294919328,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 13835058055295223248,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055295751776,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 13835058055297535648,
      "name": "type_show",
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271722508,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272450112,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275983658,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276387608,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277204334,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277565046,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277747618,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277975778,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278169032,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278494982,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279633820,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271722508,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446743936272450112,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446743936275983658,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446743936276387608,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446743936277565046,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446743936278494982,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446743936279633820,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446743936277204334,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446743936277747618,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936277975778,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446743936278169032,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579077728,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:115",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579952736,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580944240,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584804864,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585366080,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585389616,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585973264,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586916320,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587264288,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587425536,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587733952,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587800048,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587815360,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587903232,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588302816,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589571360,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077728,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071579952736,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071580944240,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584804864,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585366080,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585389616,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585973264,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071586916320,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587264288,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587425536,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587733952,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071587800048,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587815360,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071587903232,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588302816,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589571360,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579010416,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:115",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579890496,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580890304,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584735632,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585259040,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585822528,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586857488,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587032624,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587193744,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587503472,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587523296,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587622512,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588015632,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589295936,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010416,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071579890496,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071580890304,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584735632,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585259040,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585822528,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071586857488,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587032624,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587193744,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587503472,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071587523296,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071587622512,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588015632,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589295936,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579077312,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:115",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579944272,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580935488,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584806288,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585554832,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585578368,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586163072,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587164800,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587522512,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587750704,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588066912,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588136144,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588155968,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588236528,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588634640,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590013392,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077312,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071579944272,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071580935488,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584806288,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585554832,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585578368,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586163072,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071587164800,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587522512,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587750704,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588066912,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071588136144,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588155968,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071588236528,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588634640,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590013392,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
ssize_t type_show(struct kobject * kobj, struct kobj_attribute * attr, char * buf)
```

```json
{
  "name": "type_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579081408,
      "name": "type_show",
      "external": false,
      "loc": "arch/x86/kernel/ksysfs.c:115",
      "file": "arch/x86/kernel/ksysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579989632,
      "name": "type_show",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:198",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580997024,
      "name": "type_show",
      "external": false,
      "loc": "kernel/events/core.c:9921",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584911360,
      "name": "type_show",
      "external": false,
      "loc": "drivers/video/backlight/backlight.c:220",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585662784,
      "name": "type_show",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:38",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585686336,
      "name": "type_show",
      "external": false,
      "loc": "drivers/regulator/core.c:774",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586271776,
      "name": "type_show",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:403",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587271872,
      "name": "type_show",
      "external": false,
      "loc": "drivers/usb/core/endpoint.c:59",
      "file": "drivers/usb/core/endpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587634656,
      "name": "type_show",
      "external": false,
      "loc": "drivers/input/serio/serio.c:358",
      "file": "drivers/input/serio/serio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587863904,
      "name": "type_show",
      "external": false,
      "loc": "drivers/thermal/thermal_sysfs.c:27",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588184448,
      "name": "type_show",
      "external": false,
      "loc": "drivers/mmc/core/bus.c:30",
      "file": "drivers/mmc/core/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588253680,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/memmap.c:381",
      "file": "drivers/firmware/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588273376,
      "name": "type_show",
      "external": false,
      "loc": "drivers/firmware/efi/runtime-map.c:33",
      "file": "drivers/firmware/efi/runtime-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588371856,
      "name": "type_show",
      "external": false,
      "loc": "drivers/nvmem/nvmem-sysfs.c:18",
      "file": "drivers/nvmem/nvmem-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588774416,
      "name": "type_show",
      "external": false,
      "loc": "net/core/net-sysfs.c:110",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590063472,
      "name": "type_show",
      "external": false,
      "loc": "net/rfkill/core.c:678",
      "file": "net/rfkill/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081408,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071579989632,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071580997024,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584911360,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585662784,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585686336,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586271776,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071587271872,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587634656,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587863904,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071588184448,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071588253680,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588273376,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071588371856,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071588774416,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590063472,
      "name": "type_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject * k</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject * kobj</code>
</li>
</ul>
</details>
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
