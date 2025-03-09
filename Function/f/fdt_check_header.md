# Function: <code>fdt_check_header</code>

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
int fdt_check_header(const void * fdt)
```

```json
{
  "name": "fdt_check_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510855088,
      "name": "fdt_check_header",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:68",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/libstub/fdt.c:get_fdt",
        "lib/fdt_ro.c:fdt_check_full",
        "drivers/of/fdt.c:early_init_dt_verify",
        "drivers/of/fdt.c:__unflatten_device_tree",
        "drivers/of/overlay.c:of_overlay_fdt_apply",
        "lib/fdt_ro.c:fdt_check_full"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503808264,
      "name": "fdt_check_header",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int fdt_check_header(const void * fdt)
```

```json
{
  "name": "fdt_check_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236430120,
      "name": "fdt_check_header",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:68",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_verify",
        "drivers/of/fdt.c:__unflatten_device_tree",
        "drivers/of/overlay.c:of_overlay_fdt_apply",
        "lib/fdt_ro.c:fdt_check_full"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236430120,
      "name": "fdt_check_header",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int fdt_check_header(const void * fdt)
```

```json
{
  "name": "fdt_check_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297646976,
      "name": "fdt_check_header",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:68",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_verify",
        "drivers/of/fdt.c:__unflatten_device_tree",
        "drivers/of/overlay.c:of_overlay_fdt_apply",
        "lib/fdt_ro.c:fdt_check_full"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297646976,
      "name": "fdt_check_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int fdt_check_header(const void * fdt)
```

```json
{
  "name": "fdt_check_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279703794,
      "name": "fdt_check_header",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:68",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_verify",
        "drivers/of/fdt.c:__unflatten_device_tree",
        "drivers/of/overlay.c:of_overlay_fdt_apply",
        "lib/fdt_ro.c:fdt_check_full"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279703794,
      "name": "fdt_check_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int fdt_check_header(const void * fdt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fdt_check_header(const void * fdt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int fdt_check_header(const void * fdt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int fdt_check_header(const void * fdt)
```
</details>
</li>
</ul>
