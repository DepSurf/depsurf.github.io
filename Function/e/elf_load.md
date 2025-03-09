# Function: <code>elf_load</code>

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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int elf_load(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_load",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584599216,
      "name": "elf_load",
      "external": false,
      "loc": "fs/binfmt_elf.c:400",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584611568,
      "name": "elf_load",
      "external": false,
      "loc": "fs/binfmt_elf.c:400",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599216,
      "name": "elf_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
    },
    {
      "addr": 18446744071584611568,
      "name": "elf_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
long unsigned int elf_load(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```
</details>
</li>
</ul>
