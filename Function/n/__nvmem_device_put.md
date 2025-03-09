# Function: <code>__nvmem_device_put</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586863248,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:593",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863248,
      "name": "__nvmem_device_put.isra.15",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587351040,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:595",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351040,
      "name": "__nvmem_device_put.isra.15",
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587654400,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:669",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587654400,
      "name": "__nvmem_device_put.isra.13",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587786734,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:818",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_put",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588089728,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:565",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089728,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588295552,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295552,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589177088,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:805",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177088,
      "name": "__nvmem_device_put",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589172624,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:980",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589172624,
      "name": "__nvmem_device_put",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589066800,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:983",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589066800,
      "name": "__nvmem_device_put",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589785216,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:994",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785216,
      "name": "__nvmem_device_put",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591296768,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:974",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296768,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593047744,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:972",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593047744,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593499680,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:1122",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593499680,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594250320,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:1133",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_put",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594250320,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501817192,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:of_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501817192,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234336108,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:of_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234336108,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295214464,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:of_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295214464,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278164064,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:of_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278164064,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587899312,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899312,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587618592,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587618592,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588232608,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232608,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __nvmem_device_put(struct nvmem_device * nvmem)
```

```json
{
  "name": "__nvmem_device_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588367936,
      "name": "__nvmem_device_put",
      "external": false,
      "loc": "drivers/nvmem/core.c:562",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588367936,
      "name": "__nvmem_device_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __nvmem_device_put(struct nvmem_device * nvmem)
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
