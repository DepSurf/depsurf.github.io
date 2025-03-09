# Function: <code>release_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584477040,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_class.c:1245",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477040,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584822448,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_class.c:1293",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822448,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585015872,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_class.c:1328",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015872,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585103060,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_class.c:1328",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100656,
      "name": "release_firmware.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585100768,
      "name": "release_firmware",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585528963,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_class.c:1335",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527024,
      "name": "release_firmware.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585527136,
      "name": "release_firmware",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585770307,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:746",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768560,
      "name": "release_firmware.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071585768656,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585903435,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:755",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902160,
      "name": "release_firmware.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071585902256,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586143045,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141072,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071586141184,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586291525,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586289552,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071586289664,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587061613,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:976",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059184,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587059296,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587146206,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:1049",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143360,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587143472,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587033460,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:1053",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030480,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587030592,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587600473,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:1052",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587597952,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071587598064,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588938841,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:1077",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588936672,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590453220,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:1077",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590450848,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590773460,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:1132",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_nl_cmd_flash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590770992,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591116052,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:1133",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback",
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_nl_flash_update_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591113536,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499123868,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499120960,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446603336499121104,
      "name": "release_firmware",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231672060,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231669188,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 3231669312,
      "name": "release_firmware",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292312644,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292307040,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 13835058055292307248,
      "name": "release_firmware",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276439396,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276437372,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446743936276437784,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586054773,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586052800,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071586052912,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585900725,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898752,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071585898864,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586240696,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586238944,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071586239056,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void release_firmware(const struct firmware * fw)
```

```json
{
  "name": "release_firmware",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586350502,
      "name": "release_firmware",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:945",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348176,
      "name": "release_firmware.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071586348288,
      "name": "release_firmware",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
