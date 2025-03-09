# Function: <code>unregister_reboot_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510848,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:101",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510848,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524944,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:101",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524944,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548592,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:101",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548592,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535232,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:101",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535232,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579561776,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:101",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_class.c:firmware_class_exit",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561776,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590000,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:101",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590000,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579627520,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:102",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627520,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579652368,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652368,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579689488,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689488,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579729888,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729888,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579708992,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708992,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579716416,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716416,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579794869,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:105",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_unregister_reboot_notifier"
      ],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794688,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579902293,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:114",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_unregister_reboot_notifier"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902064,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054517,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:114",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_unregister_reboot_notifier"
      ],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054256,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108949,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:114",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_unregister_reboot_notifier"
      ],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108688,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580153989,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:124",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_unregister_reboot_notifier"
      ],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153728,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490867624,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_exit",
        "virt/kvm/kvm_main.c:kvm_init",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit",
        "drivers/firmware/arm_sdei.c:sdei_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490867624,
      "name": "unregister_reboot_notifier",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224885836,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224885836,
      "name": "unregister_reboot_notifier",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283698204,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_unregister_reboot_notifier"
      ],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_unregister_io_module",
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_exit",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283698112,
      "name": "unregister_reboot_notifier",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271522934,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271522934,
      "name": "unregister_reboot_notifier",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665808,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665808,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579594160,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594160,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663040,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663040,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int unregister_reboot_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_reboot_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579697072,
      "name": "unregister_reboot_notifier",
      "external": true,
      "loc": "kernel/reboot.c:104",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:firmware_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_unregister_device",
        "drivers/md/md.c:md_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697072,
      "name": "unregister_reboot_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
