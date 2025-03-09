# Function: <code>prom_getprop</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int prom_getprop(phandle node, const char * pname, void * value, size_t valuelen)
```

```json
{
  "name": "prom_getprop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302350336,
      "name": "prom_getprop",
      "external": false,
      "loc": "arch/powerpc/kernel/prom_init.c:633",
      "file": "arch/powerpc/kernel/prom_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom_init.c:prom_find_machine_type",
        "arch/powerpc/kernel/prom_init.c:prom_find_machine_type",
        "arch/powerpc/kernel/prom_init.c:prom_count_smt_threads",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init",
        "arch/powerpc/kernel/prom_init.c:prom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302350336,
      "name": "prom_getprop",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 84
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
int prom_getprop(phandle node, const char * pname, void * value, size_t valuelen)
```
</details>
</li>
</ul>
