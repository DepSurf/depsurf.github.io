# Function: <code>vmcoredd_update_program_headers</code>

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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582159787,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1340",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582254683,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1362",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582419428,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582518324,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void vmcoredd_update_program_headers(char * elfptr, size_t elfnotesz, size_t vmcoreddsz)
```

```json
{
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582822400,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
      "addr": 18446744071582822400,
      "name": "vmcoredd_update_program_headers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void vmcoredd_update_program_headers(char * elfptr, size_t elfnotesz, size_t vmcoreddsz)
```

```json
{
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582895296,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
      "addr": 18446744071582895296,
      "name": "vmcoredd_update_program_headers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582923742,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcoredd_update_size"
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583258510,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1371",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcoredd_update_size"
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583758878,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1389",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcoredd_update_size"
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584375246,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1388",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcoredd_update_size"
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584603534,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1387",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcoredd_update_size"
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584835534,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1387",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcoredd_update_size"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494147780,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227589656,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287825648,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582487060,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582424292,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582477540,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
  "name": "vmcoredd_update_program_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582558100,
      "name": "vmcoredd_update_program_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1367",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void vmcoredd_update_program_headers(char * elfptr, size_t elfnotesz, size_t vmcoreddsz)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void vmcoredd_update_program_headers(char * elfptr, size_t elfnotesz, size_t vmcoreddsz)
```
</details>
</li>
</ul>
