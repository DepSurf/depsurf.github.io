# Function: <code>bad_io_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049328,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:38",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:ioread8",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:pci_iounmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049328,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343392,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:38",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343392,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468768,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:38",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468768,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491024,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:38",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491024,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672064,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672064,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583889840,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583889840,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974080,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974080,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156192,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32_rep",
        "lib/iomap.c:iowrite16_rep",
        "lib/iomap.c:iowrite8_rep",
        "lib/iomap.c:ioread32_rep",
        "lib/iomap.c:ioread16_rep",
        "lib/iomap.c:ioread8_rep",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156192,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289936,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32_rep",
        "lib/iomap.c:iowrite16_rep",
        "lib/iomap.c:iowrite8_rep",
        "lib/iomap.c:ioread32_rep",
        "lib/iomap.c:ioread16_rep",
        "lib/iomap.c:ioread8_rep",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289936,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584700200,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
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
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584813496,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
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
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584858056,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
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
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585279512,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
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
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586131348,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
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
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587122228,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:40",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
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
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587384436,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:40",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
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
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587718788,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:40",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290441536,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290441536,
      "name": "bad_io_access.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258672,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32_rep",
        "lib/iomap.c:iowrite16_rep",
        "lib/iomap.c:iowrite8_rep",
        "lib/iomap.c:ioread32_rep",
        "lib/iomap.c:ioread16_rep",
        "lib/iomap.c:ioread8_rep",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258672,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193872,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32_rep",
        "lib/iomap.c:iowrite16_rep",
        "lib/iomap.c:iowrite8_rep",
        "lib/iomap.c:ioread32_rep",
        "lib/iomap.c:ioread16_rep",
        "lib/iomap.c:ioread8_rep",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193872,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242432,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32_rep",
        "lib/iomap.c:iowrite16_rep",
        "lib/iomap.c:iowrite8_rep",
        "lib/iomap.c:ioread32_rep",
        "lib/iomap.c:ioread16_rep",
        "lib/iomap.c:ioread8_rep",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242432,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void bad_io_access(long unsigned int port, const char * access)
```

```json
{
  "name": "bad_io_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347264,
      "name": "bad_io_access",
      "external": false,
      "loc": "lib/iomap.c:39",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iomap.c:pci_iounmap",
        "lib/iomap.c:iowrite32_rep",
        "lib/iomap.c:iowrite16_rep",
        "lib/iomap.c:iowrite8_rep",
        "lib/iomap.c:ioread32_rep",
        "lib/iomap.c:ioread16_rep",
        "lib/iomap.c:ioread8_rep",
        "lib/iomap.c:iowrite64be_hi_lo",
        "lib/iomap.c:iowrite64be_lo_hi",
        "lib/iomap.c:iowrite64_hi_lo",
        "lib/iomap.c:iowrite64_lo_hi",
        "lib/iomap.c:iowrite32be",
        "lib/iomap.c:iowrite32",
        "lib/iomap.c:iowrite16be",
        "lib/iomap.c:iowrite16",
        "lib/iomap.c:iowrite8",
        "lib/iomap.c:ioread64be_hi_lo",
        "lib/iomap.c:ioread64be_lo_hi",
        "lib/iomap.c:ioread64_hi_lo",
        "lib/iomap.c:ioread64_lo_hi",
        "lib/iomap.c:ioread32be",
        "lib/iomap.c:ioread32",
        "lib/iomap.c:ioread16be",
        "lib/iomap.c:ioread16",
        "lib/iomap.c:ioread8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347264,
      "name": "bad_io_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void bad_io_access(long unsigned int port, const char * access)
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
void bad_io_access(long unsigned int port, const char * access)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void bad_io_access(long unsigned int port, const char * access)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void bad_io_access(long unsigned int port, const char * access)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bad_io_access(long unsigned int port, const char * access)
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
