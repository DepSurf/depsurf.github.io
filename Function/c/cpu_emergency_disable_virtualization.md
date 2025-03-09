# Function: <code>cpu_emergency_disable_virtualization</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_emergency_disable_virtualization()
```

```json
{
  "name": "cpu_emergency_disable_virtualization",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579467361,
      "name": "cpu_emergency_disable_virtualization",
      "external": true,
      "loc": "arch/x86/kernel/reboot.c:839",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": [
        "arch/x86/kernel/smp.c:__sysvec_reboot",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467872,
      "name": "cpu_emergency_disable_virtualization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_emergency_disable_virtualization()
```

```json
{
  "name": "cpu_emergency_disable_virtualization",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479809,
      "name": "cpu_emergency_disable_virtualization",
      "external": true,
      "loc": "arch/x86/kernel/reboot.c:839",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": [
        "arch/x86/kernel/smp.c:__sysvec_reboot",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480320,
      "name": "cpu_emergency_disable_virtualization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_emergency_disable_virtualization()
```

```json
{
  "name": "cpu_emergency_disable_virtualization",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579510282,
      "name": "cpu_emergency_disable_virtualization",
      "external": true,
      "loc": "arch/x86/kernel/reboot.c:599",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/smp.c:__sysvec_reboot",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510384,
      "name": "cpu_emergency_disable_virtualization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void cpu_emergency_disable_virtualization()
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
