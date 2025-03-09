# Function: <code>nonseekable_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979472,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1154",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_buffers_open",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979472,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134320,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1165",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134320,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209424,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1182",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209424,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256336,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1208",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "drivers/md/dm-ioctl.c:dm_open",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256336,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395456,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1208",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_open",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "drivers/md/dm-ioctl.c:dm_open",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395456,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550032,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1249",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_open",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "drivers/md/dm-ioctl.c:dm_open",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550032,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635312,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1216",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "drivers/md/dm-ioctl.c:dm_open",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635312,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751824,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1236",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751824,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824032,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824032,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582045680,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1348",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045680,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094672,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1363",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094672,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582119712,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1385",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582119712,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436336,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1403",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436336,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953360,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1470",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953360,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583510976,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1503",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510976,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725872,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1599",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725872,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926624,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1617",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926624,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493287240,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open",
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493287240,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226890664,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open",
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226890664,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286823152,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286823152,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273034136,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open",
        "drivers/mmc/core/block.c:mmc_rpmb_chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273034136,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792768,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792768,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730432,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730432,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784080,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784080,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
int nonseekable_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "nonseekable_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853216,
      "name": "nonseekable_open",
      "external": true,
      "loc": "fs/open.c:1241",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/relay.c:relay_file_open",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "fs/libfs.c:simple_attr_open",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/debugfs/file.c:u32_array_open",
        "drivers/gpio/gpiolib.c:gpio_chrdev_open",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open",
        "drivers/xen/mcelog.c:xen_mce_chrdev_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/scsi/sg.c:sg_open",
        "drivers/md/dm-ioctl.c:dm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853216,
      "name": "nonseekable_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
