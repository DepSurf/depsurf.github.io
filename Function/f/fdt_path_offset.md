# Function: <code>fdt_path_offset</code>

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
int fdt_path_offset(const void * fdt, const char * path)
```

```json
{
  "name": "fdt_path_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510859704,
      "name": "fdt_path_offset",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:280",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/kaslr.c:kaslr_early_init",
        "arch/arm64/kernel/kaslr.c:kaslr_early_init",
        "drivers/firmware/efi/libstub/fdt.c:exit_boot_func",
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503813008,
      "name": "fdt_path_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int fdt_path_offset(const void * fdt, const char * path)
```

```json
{
  "name": "fdt_path_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236434772,
      "name": "fdt_path_offset",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:280",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236434772,
      "name": "fdt_path_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int fdt_path_offset(const void * fdt, const char * path)
```

```json
{
  "name": "fdt_path_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297653712,
      "name": "fdt_path_offset",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:280",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt",
        "arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt",
        "arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297653712,
      "name": "fdt_path_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int fdt_path_offset(const void * fdt, const char * path)
```

```json
{
  "name": "fdt_path_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279708834,
      "name": "fdt_path_offset",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:280",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279708834,
      "name": "fdt_path_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int fdt_path_offset(const void * fdt, const char * path)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fdt_path_offset(const void * fdt, const char * path)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int fdt_path_offset(const void * fdt, const char * path)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int fdt_path_offset(const void * fdt, const char * path)
```
</details>
</li>
</ul>
