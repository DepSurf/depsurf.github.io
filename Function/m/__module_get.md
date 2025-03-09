# Function: <code>__module_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920992,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1066",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/base/firmware_class.c:request_firmware",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "net/socket.c:SYSC_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920992,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952032,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1071",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_class.c:request_firmware_into_buf",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:SYSC_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952032,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983232,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1074",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_class.c:request_firmware_into_buf",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:SYSC_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983232,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579986992,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1096",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_class.c:request_firmware_into_buf",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:SYSC_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986992,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580033584,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1104",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_class.c:request_firmware_into_buf",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:SYSC_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033584,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580089520,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1103",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089520,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580136944,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1104",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136944,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580183600,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1100",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183600,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580231696,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231696,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580303536,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1117",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:cache_firmware",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303536,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580285120,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1150",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:cache_firmware",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285120,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580290448,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1058",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "lib/once.c:__do_once_done",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4_file",
        "net/sched/act_api.c:tcf_idr_create",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290448,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580442464,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1058",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "lib/once.c:__do_once_done",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/socket.c:kernel_accept",
        "net/socket.c:do_accept",
        "net/sched/act_api.c:tcf_idr_create",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442464,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580467888,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module/main.c:812",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:get_filesystem",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "lib/once.c:__do_once_done",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/socket.c:kernel_accept",
        "net/socket.c:do_accept",
        "net/sched/act_api.c:tcf_idr_create",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580467888,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580714944,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module/main.c:815",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:get_filesystem",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/elevator.c:elevator_alloc",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "lib/once.c:once_disable_jump",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/socket.c:kernel_accept",
        "net/socket.c:do_accept",
        "net/sched/act_api.c:tcf_idr_create",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714944,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580792208,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module/main.c:820",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:get_filesystem",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/elevator.c:elevator_alloc",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "lib/once.c:once_disable_jump",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/socket.c:kernel_accept",
        "net/socket.c:do_accept",
        "net/sched/act_api.c:tcf_idr_create",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792208,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580881888,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module/main.c:820",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:get_filesystem",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_test_lock",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/elevator.c:elevator_alloc",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "lib/once.c:once_disable_jump",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/socket.c:kernel_accept",
        "net/socket.c:do_accept",
        "net/sched/act_api.c:tcf_idr_create",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881888,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491475432,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491475432,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225456444,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/mtd/mtdcore.c:register_mtd_user",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/mtd/mtd_blkdevs.c:blktrans_open",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225456444,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284424512,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284424512,
      "name": "__module_get",
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271922788,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271922788,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580200496,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200496,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580147936,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147936,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580191968,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191968,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void __module_get(struct module * module)
```

```json
{
  "name": "__module_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580244688,
      "name": "__module_get",
      "external": true,
      "loc": "kernel/module.c:1114",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:set_binfmt",
        "fs/filesystems.c:get_filesystem",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/dma/dmaengine.c:dma_chan_get",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:do_bind_con_driver",
        "drivers/tty/vt/vt.c:visual_init",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/input/serio/serio.c:__serio_register_port",
        "drivers/input/input.c:input_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "net/socket.c:kernel_accept",
        "net/socket.c:__sys_accept4",
        "net/netlink/af_netlink.c:netlink_add_tap",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244688,
      "name": "__module_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
