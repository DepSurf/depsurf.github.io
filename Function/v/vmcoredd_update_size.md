# Function: <code>vmcoredd_update_size</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582159736,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1402",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582254632,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1424",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582419376,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582518272,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582822992,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582895856,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void vmcoredd_update_size(size_t dump_size)
```

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582923680,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923680,
      "name": "vmcoredd_update_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void vmcoredd_update_size(size_t dump_size)
```

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258448,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1433",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258448,
      "name": "vmcoredd_update_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void vmcoredd_update_size(size_t dump_size)
```

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583758816,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1451",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583758816,
      "name": "vmcoredd_update_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
void vmcoredd_update_size(size_t dump_size)
```

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584375184,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1450",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375184,
      "name": "vmcoredd_update_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
void vmcoredd_update_size(size_t dump_size)
```

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584603472,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1449",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584603472,
      "name": "vmcoredd_update_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
void vmcoredd_update_size(size_t dump_size)
```

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835472,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1449",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835472,
      "name": "vmcoredd_update_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494147748,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227589596,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287825604,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582487008,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582424240,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582477488,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582558048,
      "name": "vmcoredd_update_size",
      "external": false,
      "loc": "fs/proc/vmcore.c:1429",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_add_device_dump"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void vmcoredd_update_size(size_t dump_size)
```
</details>
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
