# Function: <code>stream_open</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751856,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1254",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
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
      "addr": 18446744071581751856,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824064,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
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
      "addr": 18446744071581824064,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582045712,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1366",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/socket.c:sock_alloc_file",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045712,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094704,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1381",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/socket.c:sock_alloc_file",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094704,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582119744,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1403",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/socket.c:sock_alloc_file",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582119744,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436368,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1421",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/socket.c:sock_alloc_file",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436368,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953392,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1488",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/socket.c:sock_alloc_file",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953392,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583511024,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1521",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/socket.c:sock_alloc_file",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583511024,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725920,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1617",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/socket.c:sock_alloc_file",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725920,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926672,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1635",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:create_pipe_files",
        "fs/pipe.c:create_pipe_files",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/misc/uinput.c:uinput_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "net/socket.c:sock_alloc_file",
        "net/rfkill/core.c:rfkill_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926672,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493287296,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
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
      "addr": 18446603336493287296,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226890704,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_finish_open",
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
      "addr": 3226890704,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286823184,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_finish_open",
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
      "addr": 13835058055286823184,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273034176,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_finish_open",
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
      "addr": 18446743936273034176,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792800,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
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
      "addr": 18446744071581792800,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730464,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/fuse/file.c:fuse_finish_open",
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
      "addr": 18446744071581730464,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784112,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
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
      "addr": 18446744071581784112,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int stream_open(struct inode * inode, struct file * filp)
```

```json
{
  "name": "stream_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853248,
      "name": "stream_open",
      "external": true,
      "loc": "fs/open.c:1259",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_open",
        "fs/fuse/file.c:fuse_finish_open",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open",
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
      "addr": 18446744071581853248,
      "name": "stream_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int stream_open(struct inode * inode, struct file * filp)
```
</details>
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
