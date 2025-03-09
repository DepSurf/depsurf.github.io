# Function: <code>device_find_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584377424,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:1452",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377424,
      "name": "device_find_child",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584712400,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:1452",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584712400,
      "name": "device_find_child",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584899952,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2043",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584899952,
      "name": "device_find_child",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584985376,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2041",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985376,
      "name": "device_find_child",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585407200,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2176",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407200,
      "name": "device_find_child",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585649520,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2223",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649520,
      "name": "device_find_child",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778944,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2298",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nvdimm_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778944,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586011888,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2524",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:spi_slave_store",
        "drivers/spi/spi.c:spi_slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586011888,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158816,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158816,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586916544,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:3062",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586916544,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587001120,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:3474",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587001120,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586883472,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:3701",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883472,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587445072,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:3766",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587445072,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761840,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:3800",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_suspend",
        "drivers/pwm/sysfs.c:pwm_class_resume_npwm",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761840,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590259389,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:3999",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_find_any_child"
      ],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590250688,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590578653,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:4008",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_find_any_child"
      ],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590570720,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590936541,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:4021",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_find_any_child"
      ],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590929120,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498953512,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects",
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498953512,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231524952,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231524952,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292096032,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292096032,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276336220,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/bus.c:nd_ioctl",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276336220,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585919184,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585919184,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768320,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768320,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586108832,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586108832,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct device * device_find_child(struct device * parent, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "device_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586217440,
      "name": "device_find_child",
      "external": true,
      "loc": "drivers/base/core.c:2561",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pwm/sysfs.c:pwm_class_get_state",
        "drivers/pwm/sysfs.c:pwm_unexport_child",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:slave_store",
        "drivers/spi/spi.c:slave_show",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586217440,
      "name": "device_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
