# Function: <code>__cleanup_nmi</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1887",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938976,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071579948791,
      "name": "__cleanup_nmi.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988640,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988640,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036000,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1918",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036000,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019152,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1988",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019152,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019472,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1989",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019472,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580151712,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:2018",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151712,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296736,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:2052",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296736,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580508496,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:2044",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508496,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580624,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:2050",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580624,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580644976,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:2047",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644976,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491176176,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491176176,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225202284,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225202284,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284079360,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284079360,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271728840,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271728840,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957376,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957376,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895232,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895232,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948912,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948912,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "__cleanup_nmi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995344,
      "name": "__cleanup_nmi",
      "external": false,
      "loc": "kernel/irq/manage.c:1879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995344,
      "name": "__cleanup_nmi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
const void * __cleanup_nmi(unsigned int irq, struct irq_desc * desc)
```
</details>
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
