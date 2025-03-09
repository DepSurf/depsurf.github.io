# Function: <code>intel_find_matching_signature</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int intel_find_matching_signature(void * mc, unsigned int csig, int cpf)
```

```json
{
  "name": "intel_find_matching_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310512,
      "name": "intel_find_matching_signature",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel.c:221",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:find_patch",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310512,
      "name": "intel_find_matching_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int intel_find_matching_signature(void * mc, unsigned int csig, int cpf)
```

```json
{
  "name": "intel_find_matching_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317664,
      "name": "intel_find_matching_signature",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel.c:221",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:find_patch",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch",
        "arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317664,
      "name": "intel_find_matching_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool intel_find_matching_signature(void * mc, struct cpu_signature * sig)
```

```json
{
  "name": "intel_find_matching_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415040,
      "name": "intel_find_matching_signature",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:97",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs",
        "arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415040,
      "name": "intel_find_matching_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int intel_find_matching_signature(void * mc, unsigned int csig, int cpf)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpu_signature * sig</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int csig</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpf</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>
