# Function: <code>rproc_va_to_pa</code>

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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588230880,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:144",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230880,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589106256,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:147",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589106256,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589105312,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:146",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105312,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588994928,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:146",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588994928,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589708848,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:147",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589708848,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591216192,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:147",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591216192,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592961408,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:146",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592961408,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593411776,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:146",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593411776,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594157488,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:146",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_registered_carveouts",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594157488,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501687192,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:144",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501687192,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234212608,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:144",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234212608,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295120704,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:144",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295120704,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587842576,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:144",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587842576,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```

```json
{
  "name": "rproc_va_to_pa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588303216,
      "name": "rproc_va_to_pa",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:144",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_fw_boot",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303216,
      "name": "rproc_va_to_pa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
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
phys_addr_t rproc_va_to_pa(void * cpu_addr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
phys_addr_t rproc_va_to_pa(void * cpu_addr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
