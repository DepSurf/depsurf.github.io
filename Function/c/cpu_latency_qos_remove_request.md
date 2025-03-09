# Function: <code>cpu_latency_qos_remove_request</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```

```json
{
  "name": "cpu_latency_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579965549,
      "name": "cpu_latency_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:316",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:cpu_latency_qos_release"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/power/qos.c:cpu_latency_qos_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965280,
      "name": "cpu_latency_qos_remove_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071579965456,
      "name": "cpu_latency_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```

```json
{
  "name": "cpu_latency_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579953517,
      "name": "cpu_latency_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:316",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:cpu_latency_qos_release"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/power/qos.c:cpu_latency_qos_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953280,
      "name": "cpu_latency_qos_remove_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071579953424,
      "name": "cpu_latency_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```

```json
{
  "name": "cpu_latency_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579956304,
      "name": "cpu_latency_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:316",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/power/qos.c:cpu_latency_qos_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956304,
      "name": "cpu_latency_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```

```json
{
  "name": "cpu_latency_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580085664,
      "name": "cpu_latency_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:316",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/power/qos.c:cpu_latency_qos_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085664,
      "name": "cpu_latency_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```

```json
{
  "name": "cpu_latency_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580222144,
      "name": "cpu_latency_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:316",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/power/qos.c:cpu_latency_qos_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222144,
      "name": "cpu_latency_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```

```json
{
  "name": "cpu_latency_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580412928,
      "name": "cpu_latency_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:316",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/power/qos.c:cpu_latency_qos_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580412928,
      "name": "cpu_latency_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```

```json
{
  "name": "cpu_latency_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580481616,
      "name": "cpu_latency_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:316",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/power/qos.c:cpu_latency_qos_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481616,
      "name": "cpu_latency_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```

```json
{
  "name": "cpu_latency_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541456,
      "name": "cpu_latency_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:321",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/power/qos.c:cpu_latency_qos_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541456,
      "name": "cpu_latency_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request * req)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
