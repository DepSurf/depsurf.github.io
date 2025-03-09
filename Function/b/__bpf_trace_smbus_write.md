# Function: <code>__bpf_trace_smbus_write</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587063296,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:27",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063296,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587223344,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:27",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587223344,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587489840,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587489840,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587693008,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693008,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588561184,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588561184,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588585888,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588585888,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588469360,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588469360,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589137536,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137536,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590588544,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590588544,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592244624,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592244624,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592669888,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592669888,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593415280,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593415280,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500851528,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500851528,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233369464,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233369464,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294318128,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294318128,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587644256,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587644256,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```

```json
{
  "name": "__bpf_trace_smbus_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587755456,
      "name": "__bpf_trace_smbus_write",
      "external": false,
      "loc": "include/trace/events/smbus.h:23",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755456,
      "name": "__bpf_trace_smbus_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void __bpf_trace_smbus_write(void * __data, const struct i2c_adapter * adap, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, const union i2c_smbus_data * data)
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
