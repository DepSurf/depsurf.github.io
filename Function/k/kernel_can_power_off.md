# Function: <code>kernel_can_power_off</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kernel_can_power_off()
```

```json
{
  "name": "kernel_can_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579906431,
      "name": "kernel_can_power_off",
      "external": true,
      "loc": "kernel/reboot.c:649",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902448,
      "name": "kernel_can_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kernel_can_power_off()
```

```json
{
  "name": "kernel_can_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580059285,
      "name": "kernel_can_power_off",
      "external": true,
      "loc": "kernel/reboot.c:666",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054720,
      "name": "kernel_can_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
bool kernel_can_power_off()
```

```json
{
  "name": "kernel_can_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580113702,
      "name": "kernel_can_power_off",
      "external": true,
      "loc": "kernel/reboot.c:666",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109152,
      "name": "kernel_can_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
bool kernel_can_power_off()
```

```json
{
  "name": "kernel_can_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580158886,
      "name": "kernel_can_power_off",
      "external": true,
      "loc": "kernel/reboot.c:681",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:__do_sys_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_power_off",
        "kernel/power/hibernate.c:hibernate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154192,
      "name": "kernel_can_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool kernel_can_power_off()
```
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
