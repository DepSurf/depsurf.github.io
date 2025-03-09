# Function: <code>__bpf_trace_spi_message</code>

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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586377184,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586377184,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586517840,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517840,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586762320,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762320,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586908768,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586908768,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727504,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587787008,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666272,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:102",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255088,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:102",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589638080,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:102",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591240080,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:102",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603808,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:102",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592335024,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499862832,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499862832,
      "name": "__bpf_trace_spi_message",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232422608,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232422608,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293187360,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293187360,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586665792,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665792,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586534128,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534128,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586863328,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863328,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
```

```json
{
  "name": "__bpf_trace_spi_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586969440,
      "name": "__bpf_trace_spi_message",
      "external": false,
      "loc": "include/trace/events/spi.h:45",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586969440,
      "name": "__bpf_trace_spi_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
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
void __bpf_trace_spi_message(void * __data, struct spi_message * msg)
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
