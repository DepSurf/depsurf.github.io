# Function: <code>request_microcode_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163472,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1021",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579164896,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:931",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163472,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579164896,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163360,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1079",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579165296,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:941",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163360,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579165296,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579172976,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:930",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579175152,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:943",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579172976,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579175152,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579173088,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:950",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579174896,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:756",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173088,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579174896,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579187936,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1002",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579190272,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:771",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187936,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579190272,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579199328,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1010",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579202000,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:779",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199328,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579202000,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579188720,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1010",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579191184,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:925",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188720,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579191184,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579201456,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1000",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579204064,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:923",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201456,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579204064,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579203712,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1000",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579206320,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:923",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203712,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579206320,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224896,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1001",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579227120,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:923",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224896,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579227120,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579218880,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:958",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220624,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:922",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218880,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579220624,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221360,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:958",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579223120,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:922",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221360,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579223120,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579259888,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:958",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579261712,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:922",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259888,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579261712,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311808,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:920",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579313632,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:928",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311808,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071579313632,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579202560,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1000",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579205168,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:923",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202560,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579205168,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579137520,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1000",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579140128,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:923",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137520,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579140128,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579203632,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1000",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579206240,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:923",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203632,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579206240,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```

```json
{
  "name": "request_microcode_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579208912,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1000",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579211520,
      "name": "request_microcode_user",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:923",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208912,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071579211520,
      "name": "request_microcode_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
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
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
enum ucode_state request_microcode_user(int cpu, const void * buf, size_t size)
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
