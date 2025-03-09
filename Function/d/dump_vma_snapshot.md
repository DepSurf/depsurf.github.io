# Function: <code>dump_vma_snapshot</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int dump_vma_snapshot(struct coredump_params * cprm, int * vma_count, struct core_vma_metadata * * vma_meta, size_t * vma_data_size_ptr)
```

```json
{
  "name": "dump_vma_snapshot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750368,
      "name": "dump_vma_snapshot",
      "external": true,
      "loc": "fs/coredump.c:1072",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750368,
      "name": "dump_vma_snapshot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int dump_vma_snapshot(struct coredump_params * cprm, int * vma_count, struct core_vma_metadata * * vma_meta, size_t * vma_data_size_ptr)
```

```json
{
  "name": "dump_vma_snapshot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582779392,
      "name": "dump_vma_snapshot",
      "external": true,
      "loc": "fs/coredump.c:1090",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779392,
      "name": "dump_vma_snapshot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
int dump_vma_snapshot(struct coredump_params * cprm, int * vma_count, struct core_vma_metadata * * vma_meta, size_t * vma_data_size_ptr)
```

```json
{
  "name": "dump_vma_snapshot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583106672,
      "name": "dump_vma_snapshot",
      "external": true,
      "loc": "fs/coredump.c:1097",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583106672,
      "name": "dump_vma_snapshot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
bool dump_vma_snapshot(struct coredump_params * cprm)
```

```json
{
  "name": "dump_vma_snapshot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582448,
      "name": "dump_vma_snapshot",
      "external": false,
      "loc": "fs/coredump.c:1120",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582448,
      "name": "dump_vma_snapshot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
bool dump_vma_snapshot(struct coredump_params * cprm)
```

```json
{
  "name": "dump_vma_snapshot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584185792,
      "name": "dump_vma_snapshot",
      "external": false,
      "loc": "fs/coredump.c:1145",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185792,
      "name": "dump_vma_snapshot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
bool dump_vma_snapshot(struct coredump_params * cprm)
```

```json
{
  "name": "dump_vma_snapshot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584413392,
      "name": "dump_vma_snapshot",
      "external": false,
      "loc": "fs/coredump.c:1145",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584413392,
      "name": "dump_vma_snapshot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
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
bool dump_vma_snapshot(struct coredump_params * cprm)
```

```json
{
  "name": "dump_vma_snapshot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584634128,
      "name": "dump_vma_snapshot",
      "external": false,
      "loc": "fs/coredump.c:1183",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634128,
      "name": "dump_vma_snapshot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int dump_vma_snapshot(struct coredump_params * cprm, int * vma_count, struct core_vma_metadata * * vma_meta, size_t * vma_data_size_ptr)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int * vma_count</code>
</li>
<li>
<b>Param removed. </b>
<code>struct core_vma_metadata * * vma_meta</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t * vma_data_size_ptr</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
