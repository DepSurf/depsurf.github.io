# Function: <code>acpi_ex_acquire_mutex_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583653700,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:160",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653700,
      "name": "acpi_ex_acquire_mutex_object",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583978078,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:160",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978078,
      "name": "acpi_ex_acquire_mutex_object",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119474,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:160",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584119474,
      "name": "acpi_ex_acquire_mutex_object",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584186594,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:160",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186594,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503375,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:160",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503375,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584727949,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727949,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584827591,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827591,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585031201,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031201,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167286,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167286,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585872559,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872559,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585993690,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993690,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585870728,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870728,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586358097,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586358097,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587605551,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587605551,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588900144,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900144,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589190064,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190064,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589496480,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589496480,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497520656,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497520656,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585054538,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054538,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970083,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970083,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118870,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118870,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```

```json
{
  "name": "acpi_ex_acquire_mutex_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585225030,
      "name": "acpi_ex_acquire_mutex_object",
      "external": true,
      "loc": "drivers/acpi/acpica/exmutex.c:126",
      "file": "drivers/acpi/acpica/exmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585225030,
      "name": "acpi_ex_acquire_mutex_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object * obj_desc, u64 thread_id)
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
