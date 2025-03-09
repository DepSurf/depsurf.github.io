# Function: <code>generic_handle_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738032,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:344",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/gpio/gpio-intel-mid.c:intel_mid_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/gpio/gpio-zx.c:zx_irq_handler",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738032,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579759728,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:402",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/gpio/gpio-zx.c:zx_irq_handler",
        "drivers/pci/host/pcie-designware.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759728,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785904,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/host/pcie-designware.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785904,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783360,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:607",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783360,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816736,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:600",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816736,
      "name": "generic_handle_irq",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850464,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:617",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850464,
      "name": "generic_handle_irq",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897456,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:622",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897456,
      "name": "generic_handle_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932272,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932272,
      "name": "generic_handle_irq",
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982400,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982400,
      "name": "generic_handle_irq",
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029936,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-msic.c:msic_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:consume_one_event",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029936,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013520,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:640",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/gpio/gpio-msic.c:msic_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013520,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014416,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:640",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014416,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146496,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:656",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146496,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293760,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:661",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293760,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504464,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:664",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504464,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576544,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:685",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576544,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580640832,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:685",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640832,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491168368,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/irq-bcm2835.c:bcm2836_chained_handle_irq",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler",
        "drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_handle_irq",
        "drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_handle_irq",
        "drivers/irqchip/irq-gic.c:gic_handle_cascade_irq",
        "drivers/irqchip/irq-partition-percpu.c:partition_handle_irq",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle",
        "drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handle_bank",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler",
        "drivers/gpio/gpio-davinci.c:gpio_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_cascade",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler",
        "drivers/gpio/gpio-pl061.c:pl061_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_handle_msi_irq",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_isr",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_handler",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_handler",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify",
        "drivers/edac/altera_edac.c:altr_edac_a10_irq_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491168368,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225194184,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler",
        "arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler",
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler",
        "drivers/irqchip/irq-orion.c:orion_bridge_irq_handler",
        "drivers/irqchip/irq-gic.c:gic_handle_cascade_irq",
        "drivers/irqchip/irq-partition-percpu.c:partition_handle_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_handler",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_eint0_15",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_irq",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-htc-egpio.c:egpio_handler",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_cascade",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_handler",
        "drivers/gpio/gpio-pl061.c:pl061_irq_handler",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_isr",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_handler",
        "drivers/soc/dove/pmu.c:pmu_irq_handler",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/t7l66xb.c:t7l66xb_irq",
        "drivers/mfd/tc6393xb.c:tc6393xb_irq",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify",
        "drivers/memory/omap-gpmc.c:gpmc_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225194184,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284067216,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/irq.c:__do_irq",
        "arch/powerpc/sysdev/mpic.c:mpic_cascade",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events",
        "arch/powerpc/platforms/pseries/setup.c:pseries_8259_cascade",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284067216,
      "name": "generic_handle_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271720774,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/irq-sifive-plic.c:plic_handle_irq",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271720774,
      "name": "generic_handle_irq",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951136,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951136,
      "name": "generic_handle_irq",
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889024,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889024,
      "name": "generic_handle_irq",
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942672,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942672,
      "name": "generic_handle_irq",
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
int generic_handle_irq(unsigned int irq)
```

```json
{
  "name": "generic_handle_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989056,
      "name": "generic_handle_irq",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:638",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989056,
      "name": "generic_handle_irq",
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
