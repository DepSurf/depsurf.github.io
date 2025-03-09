# Function: <code>vfio_send_intx_eventfd</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587071040,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071040,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587916771,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587913552,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587977939,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974752,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587860356,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587857152,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588465461,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462656,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071592551131,
      "name": "vfio_send_intx_eventfd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589868410,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589865360,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071594430497,
      "name": "vfio_send_intx_eventfd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293402672,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293402672,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718960,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718960,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025600,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025600,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void vfio_send_intx_eventfd(void * opaque, void * unused)
```

```json
{
  "name": "vfio_send_intx_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587132768,
      "name": "vfio_send_intx_eventfd",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:28",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132768,
      "name": "vfio_send_intx_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void vfio_send_intx_eventfd(void * opaque, void * unused)
```
</details>
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
void vfio_send_intx_eventfd(void * opaque, void * unused)
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
void vfio_send_intx_eventfd(void * opaque, void * unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void vfio_send_intx_eventfd(void * opaque, void * unused)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void vfio_send_intx_eventfd(void * opaque, void * unused)
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
void vfio_send_intx_eventfd(void * opaque, void * unused)
```
</details>
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
