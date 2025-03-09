# Function: <code>ima_dump_measurement_list</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_dump_measurement_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_dump_measurement_list",
      "external": false,
      "loc": "security/integrity/ima/ima_kexec.c:18",
      "file": "security/integrity/ima/ima_kexec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188560,
      "name": "ima_dump_measurement_list.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071596103041,
      "name": "ima_dump_measurement_list.constprop.0.isra.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_dump_measurement_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_dump_measurement_list",
      "external": false,
      "loc": "security/integrity/ima/ima_kexec.c:18",
      "file": "security/integrity/ima/ima_kexec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426288,
      "name": "ima_dump_measurement_list.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071596626147,
      "name": "ima_dump_measurement_list.constprop.0.isra.0.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_dump_measurement_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_dump_measurement_list",
      "external": false,
      "loc": "security/integrity/ima/ima_kexec.c:18",
      "file": "security/integrity/ima/ima_kexec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691360,
      "name": "ima_dump_measurement_list.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071597531761,
      "name": "ima_dump_measurement_list.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ima_dump_measurement_list(long unsigned int * buffer_size, void * * buffer, long unsigned int segment_size)
```

```json
{
  "name": "ima_dump_measurement_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289733600,
      "name": "ima_dump_measurement_list",
      "external": false,
      "loc": "security/integrity/ima/ima_kexec.c:17",
      "file": "security/integrity/ima/ima_kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289733600,
      "name": "ima_dump_measurement_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int ima_dump_measurement_list(long unsigned int * buffer_size, void * * buffer, long unsigned int segment_size)
```
</details>
</li>
</ul>
