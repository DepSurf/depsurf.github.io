# Function: <code>call_on_cpu</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289824,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:912",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289824,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687232,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:912",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687232,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584914352,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:913",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914352,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585018256,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:913",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018256,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585221952,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:900",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221952,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585358384,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:900",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358384,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_on_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579273725,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:300",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586067888,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:300",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
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
  "name": "call_on_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579281053,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:300",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586189840,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:300",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
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
  "name": "call_on_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579283805,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:300",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586064780,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:300",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
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
  "name": "call_on_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579327550,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:300",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559444,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:300",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
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
  "name": "call_on_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579388365,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:305",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587819165,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:305",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
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
  "name": "call_on_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579465981,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:305",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589161654,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:305",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
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
  "name": "call_on_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579478483,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:305",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589454966,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:305",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
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
  "name": "call_on_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579509251,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:305",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589762954,
      "name": "call_on_cpu",
      "external": false,
      "loc": "include/acpi/processor.h:305",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585159152,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:900",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159152,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585073120,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:900",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073120,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585309968,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:900",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585309968,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```

```json
{
  "name": "call_on_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585416112,
      "name": "call_on_cpu",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:900",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416112,
      "name": "call_on_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int call_on_cpu(int cpu, long int (*)(void *) fn, void * arg, bool direct)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
