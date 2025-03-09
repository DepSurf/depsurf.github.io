# Function: <code>fdt_setprop_inplace</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fdt_setprop_inplace(void * fdt, int nodeoffset, const char * name, const void * val, int len)
```

```json
{
  "name": "fdt_setprop_inplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510868264,
      "name": "fdt_setprop_inplace",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_wip.c:33",
      "file": "lib/fdt_wip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/libstub/fdt.c:exit_boot_func",
        "drivers/firmware/efi/libstub/fdt.c:exit_boot_func",
        "drivers/firmware/efi/libstub/fdt.c:exit_boot_func",
        "drivers/firmware/efi/libstub/fdt.c:exit_boot_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503819824,
      "name": "fdt_setprop_inplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int fdt_setprop_inplace(void * fdt, int nodeoffset, const char * name, const void * val, int len)
```

```json
{
  "name": "fdt_setprop_inplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236441240,
      "name": "fdt_setprop_inplace",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_wip.c:33",
      "file": "lib/fdt_wip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236441240,
      "name": "fdt_setprop_inplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int fdt_setprop_inplace(void * fdt, int nodeoffset, const char * name, const void * val, int len)
```

```json
{
  "name": "fdt_setprop_inplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297663616,
      "name": "fdt_setprop_inplace",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_wip.c:33",
      "file": "lib/fdt_wip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297663616,
      "name": "fdt_setprop_inplace",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fdt_setprop_inplace(void * fdt, int nodeoffset, const char * name, const void * val, int len)
```

```json
{
  "name": "fdt_setprop_inplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279715862,
      "name": "fdt_setprop_inplace",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_wip.c:33",
      "file": "lib/fdt_wip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279715862,
      "name": "fdt_setprop_inplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int fdt_setprop_inplace(void * fdt, int nodeoffset, const char * name, const void * val, int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fdt_setprop_inplace(void * fdt, int nodeoffset, const char * name, const void * val, int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int fdt_setprop_inplace(void * fdt, int nodeoffset, const char * name, const void * val, int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int fdt_setprop_inplace(void * fdt, int nodeoffset, const char * name, const void * val, int len)
```
</details>
</li>
</ul>
