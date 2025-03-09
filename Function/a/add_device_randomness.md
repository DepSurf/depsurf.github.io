# Function: <code>add_device_randomness</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159888,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:759",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:__dev_open",
        "net/core/dev.c:register_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159888,
      "name": "add_device_randomness",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584500192,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:996",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584500192,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679248,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:996",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679248,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584766256,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:980",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584766256,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585186352,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:979",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186352,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417536,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1087",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417536,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585540864,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1100",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585540864,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585767424,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767424,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585910064,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585910064,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586648928,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1124",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:__exit_signal",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586648928,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586759568,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1124",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:__exit_signal",
        "lib/random32.c:prandom_seed",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759568,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586640336,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1114",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:__exit_signal",
        "lib/random32.c:prandom_seed",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586640336,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587187216,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1134",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:__exit_signal",
        "lib/random32.c:prandom_seed",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587187216,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
void add_device_randomness(const void * buf, size_t len)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588494288,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:829",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "drivers/char/random.c:add_vmfork_randomness",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_decode_cid",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588494288,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void add_device_randomness(const void * buf, size_t len)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589931440,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:917",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:__exit_signal",
        "kernel/sys.c:__ia32_sys_setdomainname",
        "kernel/sys.c:__x64_sys_setdomainname",
        "kernel/sys.c:__ia32_sys_sethostname",
        "kernel/sys.c:__x64_sys_sethostname",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "drivers/char/random.c:add_vmfork_randomness",
        "drivers/char/random.c:random_init",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_decode_cid",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589931440,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void add_device_randomness(const void * buf, size_t len)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590240816,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:917",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:__exit_signal",
        "kernel/sys.c:__ia32_sys_setdomainname",
        "kernel/sys.c:__x64_sys_setdomainname",
        "kernel/sys.c:__ia32_sys_sethostname",
        "kernel/sys.c:__x64_sys_sethostname",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "drivers/char/random.c:add_vmfork_randomness",
        "drivers/char/random.c:random_init",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_decode_cid",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590240816,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void add_device_randomness(const void * buf, size_t len)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590581840,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:917",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:__exit_signal",
        "kernel/sys.c:__ia32_sys_setdomainname",
        "kernel/sys.c:__x64_sys_setdomainname",
        "kernel/sys.c:__ia32_sys_sethostname",
        "kernel/sys.c:__x64_sys_sethostname",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "drivers/char/random.c:add_vmfork_randomness",
        "drivers/char/random.c:random_init",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_decode_cid",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_set_mac_address",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590581840,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498746944,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498746944,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231350160,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/arm/mach-omap2/id.c:__omap_feed_randpool",
        "kernel/exit.c:release_task",
        "drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init",
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_init",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231350160,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291885408,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291885408,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276235816,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276235816,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585671056,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/random.c:add_bootloader_randomness",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671056,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585524480,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524480,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585860464,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585860464,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void add_device_randomness(const void * buf, unsigned int size)
```

```json
{
  "name": "add_device_randomness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585968336,
      "name": "add_device_randomness",
      "external": true,
      "loc": "drivers/char/random.c:1177",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/exit.c:release_task",
        "drivers/char/hw_random/core.c:add_early_randomness",
        "drivers/mfd/wm831x-otp.c:wm831x_otp_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968336,
      "name": "add_device_randomness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size</code>
</li>
</ul>
</details>
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
