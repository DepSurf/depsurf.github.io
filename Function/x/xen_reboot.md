# Function: <code>xen_reboot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578961216,
      "name": "xen_reboot",
      "external": false,
      "loc": "arch/x86/xen/enlighten.c:1274",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_event",
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten.c:xen_machine_power_off",
        "arch/x86/xen/enlighten.c:xen_machine_halt",
        "arch/x86/xen/enlighten.c:xen_restart",
        "arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten.c:xen_hvm_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578961216,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957776,
      "name": "xen_reboot",
      "external": false,
      "loc": "arch/x86/xen/enlighten.c:1293",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten.c:xen_panic_event",
        "arch/x86/xen/enlighten.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten.c:xen_machine_power_off",
        "arch/x86/xen/enlighten.c:xen_machine_halt",
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957776,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578959856,
      "name": "xen_reboot",
      "external": false,
      "loc": "arch/x86/xen/enlighten.c:1281",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten.c:xen_panic_event",
        "arch/x86/xen/enlighten.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten.c:xen_machine_power_off",
        "arch/x86/xen/enlighten.c:xen_machine_halt",
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578959856,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578950816,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:246",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_event",
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578950816,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578953024,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:250",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_event",
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953024,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955504,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:258",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_event",
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955504,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957504,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_event",
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957504,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578964464,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_panic_event",
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964464,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578966896,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966896,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578976096,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976096,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578978816,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978816,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578987936,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987936,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579004640,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:303",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart",
        "drivers/xen/efi.c:xen_efi_reset_system",
        "drivers/xen/efi.c:xen_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579004640,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021424,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:239",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021424,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049248,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:239",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049248,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049248,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:239",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049248,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579074576,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:243",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579074576,
      "name": "xen_reboot",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490615296,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/arm/xen/enlighten.c:174",
      "file": "arch/arm/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/xen/enlighten.c:xen_power_off",
        "arch/arm/xen/enlighten.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490615296,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578966896,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966896,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578966832,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966832,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void xen_reboot(int reason)
```

```json
{
  "name": "xen_reboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967424,
      "name": "xen_reboot",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:260",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_emergency_restart",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_crash_shutdown",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_crash_shutdown",
        "arch/x86/xen/enlighten_pv.c:xen_machine_power_off",
        "arch/x86/xen/enlighten_pv.c:xen_machine_halt",
        "arch/x86/xen/enlighten_pv.c:xen_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967424,
      "name": "xen_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_reboot(int reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_reboot(int reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_reboot(int reason)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_reboot(int reason)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
