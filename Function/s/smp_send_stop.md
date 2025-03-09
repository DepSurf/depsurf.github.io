# Function: <code>smp_send_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580465655,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:81",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580542764,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579239875,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:68",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580606808,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:68",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235923,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:68",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579388039,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:68",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic",
        "kernel/panic.c:crash_smp_send_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579252326,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:69",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579415360,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:69",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic",
        "kernel/panic.c:crash_smp_send_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579263782,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:69",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579429568,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:69",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579288358,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:69",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579463194,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:69",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579304742,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579480982,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579308838,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579506882,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579338564,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535067,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579338569,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:60",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591277203,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:60",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579342302,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:60",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591220101,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:60",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399742,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:60",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592098641,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:60",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579465639,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:67",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593866020,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:67",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556761,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:56",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805243,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:56",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579569049,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:58",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853041,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:58",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579598046,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:52",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579891142,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:52",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void smp_send_stop()
```

```json
{
  "name": "smp_send_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490274832,
      "name": "smp_send_stop",
      "external": true,
      "loc": "arch/arm64/kernel/smp.c:969",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:machine_restart",
        "arch/arm64/kernel/process.c:machine_power_off",
        "arch/arm64/kernel/process.c:machine_halt",
        "kernel/panic.c:panic",
        "kernel/panic.c:crash_smp_send_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490274832,
      "name": "smp_send_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
void smp_send_stop()
```

```json
{
  "name": "smp_send_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224451224,
      "name": "smp_send_stop",
      "external": true,
      "loc": "arch/arm/kernel/smp.c:708",
      "file": "arch/arm/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/reboot.c:machine_restart",
        "arch/arm/kernel/reboot.c:machine_power_off",
        "arch/arm/kernel/reboot.c:machine_halt",
        "kernel/panic.c:panic",
        "kernel/panic.c:crash_smp_send_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224451224,
      "name": "smp_send_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void smp_send_stop()
```

```json
{
  "name": "smp_send_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282513776,
      "name": "smp_send_stop",
      "external": true,
      "loc": "arch/powerpc/kernel/smp.c:596",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:machine_halt",
        "arch/powerpc/kernel/setup-common.c:machine_power_off",
        "arch/powerpc/kernel/setup-common.c:machine_restart",
        "arch/powerpc/platforms/powernv/opal.c:pnv_platform_error_reboot",
        "kernel/panic.c:panic",
        "kernel/panic.c:crash_smp_send_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282513776,
      "name": "smp_send_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void smp_send_stop()
```

```json
{
  "name": "smp_send_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271351860,
      "name": "smp_send_stop",
      "external": true,
      "loc": "arch/riscv/kernel/smp.c:182",
      "file": "arch/riscv/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:crash_smp_send_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271351860,
      "name": "smp_send_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579304742,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579480546,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579239206,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579409436,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579304742,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579480466,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_stop",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579312934,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579512329,
      "name": "smp_send_stop",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:70",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void smp_send_stop()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void smp_send_stop()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void smp_send_stop()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void smp_send_stop()
```
</details>
</li>
</ul>
