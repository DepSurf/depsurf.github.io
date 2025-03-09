# Function: <code>wait_for_completion_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368992,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:139",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/misc/bmp085.c:bmp085_update_raw_temperature",
        "drivers/misc/bmp085.c:show_pressure",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368992,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587870160,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:139",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587870160,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588084720,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:139",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588084720,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588311904,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:142",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311904,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588876672,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:156",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/tty/serdev/core.c:serdev_device_write",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588876672,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589255792,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/tty/serdev/core.c:serdev_device_write",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255792,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589498016,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589498016,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589958016,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/soundwire/stream.c:do_bank_switch",
        "drivers/soundwire/stream.c:sdw_prep_deprep_ports"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589958016,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590185680,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185680,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591203552,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:155",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "fs/io_uring.c:io_ring_exit_work",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591203552,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591698688,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:155",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "fs/io_uring.c:io_ring_exit_work",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591698688,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591641200,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:155",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "fs/io_uring.c:io_ring_exit_work",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/vfio/vfio.c:vfio_unregister_group_dev",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "net/core/selftests.c:__net_test_loopback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591641200,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592815120,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:155",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_ring_exit_work",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/vfio/vfio.c:vfio_unregister_group_dev",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "net/core/selftests.c:__net_test_loopback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592815120,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594717296,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:155",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "io_uring/io_uring.c:io_ring_exit_work",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/vfio/vfio.c:vfio_unregister_group_dev",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "net/core/selftests.c:__net_test_loopback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594717296,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596465280,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:155",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "io_uring/io_uring.c:io_ring_exit_work",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "net/core/selftests.c:__net_test_loopback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596465280,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597006384,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:155",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "security/apparmor/notify.c:aa_do_notification",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "net/core/selftests.c:__net_test_loopback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597006384,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597935680,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:165",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "security/apparmor/notify.c:aa_do_notification",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/gpu/drm/drm_atomic.c:drm_crtc_commit_wait",
        "drivers/gpu/drm/drm_atomic.c:drm_crtc_commit_wait",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_flip_done",
        "drivers/spi/spi.c:spi_transfer_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume",
        "drivers/input/serio/i8042.c:i8042_check_aux",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "net/core/selftests.c:__net_test_loopback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597935680,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503929456,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/smp.c:__cpu_up",
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/video/fbdev/mx3fb.c:mx3fb_pan_display",
        "drivers/soc/qcom/rpmh.c:rpmh_write_batch",
        "drivers/soc/qcom/rpmh.c:rpmh_write",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/firmware/raspberrypi.c:rpi_firmware_property_list",
        "drivers/firmware/ti_sci.c:ti_sci_probe",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_get_status",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_control",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_config",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_handover",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_release",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_proc_request",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_flow_cfg",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_ch_cfg",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_tx_ch_cfg",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_unpair",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_pair",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_ring_get_config",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_ring_config",
        "drivers/firmware/ti_sci.c:ti_sci_get_resource_range",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_core_reboot",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_freq",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_freq",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_match_freq",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_num_parents",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_parent",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_parent",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_get_clock_state",
        "drivers/firmware/ti_sci.c:ti_sci_set_clock_state",
        "drivers/firmware/ti_sci.c:ti_sci_cmd_set_device_resets",
        "drivers/firmware/ti_sci.c:ti_sci_get_device_state",
        "drivers/firmware/ti_sci.c:ti_sci_set_device_state",
        "drivers/firmware/arm_scmi/driver.c:scmi_do_xfer_with_response",
        "drivers/firmware/arm_scmi/driver.c:scmi_do_xfer",
        "drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503929456,
      "name": "wait_for_completion_timeout",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236539592,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp.c:__cpu_up",
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/video/fbdev/mx3fb.c:mx3fb_pan_display",
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_wait",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_read",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg",
        "drivers/firmware/arm_scmi/driver.c:scmi_do_xfer_with_response",
        "drivers/firmware/arm_scmi/driver.c:scmi_do_xfer",
        "drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_clk_change_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236539592,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297778848,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297778848,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279797722,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/smpboot.c:__cpu_up",
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279797722,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589787968,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/block/xen-blkfront.c:blkfront_freeze",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589787968,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589510496,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/storvsc_drv.c:storvsc_host_reset_handler",
        "drivers/scsi/storvsc_drv.c:storvsc_channel_init",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/hv/vmbus_drv.c:hv_acpi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589510496,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590231376,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_check_cmd_completion",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590231376,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
long unsigned int wait_for_completion_timeout(struct completion * x, long unsigned int timeout)
```

```json
{
  "name": "wait_for_completion_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590282224,
      "name": "wait_for_completion_timeout",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:__kthread_create_on_node",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq",
        "drivers/mfd/wm8350-core.c:wm8350_read_auxadc",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/da9052-core.c:da9052_adc_manual_read",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mailbox/mailbox.c:mbox_send_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590282224,
      "name": "wait_for_completion_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
