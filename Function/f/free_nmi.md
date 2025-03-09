# Function: <code>free_nmi</code>

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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1913",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949236,
      "name": "free_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579947200,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579997344,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997344,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044608,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1944",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044608,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027808,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:2014",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027808,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028528,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:2015",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028528,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161008,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:2044",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161008,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306960,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:2078",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306960,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580519504,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:2070",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519504,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580592432,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:2076",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580592432,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580656912,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:2073",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656912,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491188224,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491188224,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225210992,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225210992,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284091744,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284091744,
      "name": "free_nmi",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271734822,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271734822,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966080,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966080,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579903920,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903920,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957616,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957616,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
```

```json
{
  "name": "free_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580004000,
      "name": "free_nmi",
      "external": true,
      "loc": "kernel/irq/manage.c:1905",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004000,
      "name": "free_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
const void * free_nmi(unsigned int irq, void * dev_id)
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
