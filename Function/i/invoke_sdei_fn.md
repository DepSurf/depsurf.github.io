# Function: <code>invoke_sdei_fn</code>

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
int invoke_sdei_fn(long unsigned int function_id, long unsigned int arg0, long unsigned int arg1, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, u64 * result)
```

```json
{
  "name": "invoke_sdei_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501474536,
      "name": "invoke_sdei_fn",
      "external": false,
      "loc": "drivers/firmware/arm_sdei.c:139",
      "file": "drivers/firmware/arm_sdei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/arm_sdei.c:sdei_probe",
        "drivers/firmware/arm_sdei.c:sdei_register_ghes",
        "drivers/firmware/arm_sdei.c:sdei_device_thaw",
        "drivers/firmware/arm_sdei.c:sdei_event_register",
        "drivers/firmware/arm_sdei.c:sdei_event_register",
        "drivers/firmware/arm_sdei.c:_local_event_register",
        "drivers/firmware/arm_sdei.c:_local_event_unregister",
        "drivers/firmware/arm_sdei.c:sdei_event_disable",
        "drivers/firmware/arm_sdei.c:_ipi_event_disable",
        "drivers/firmware/arm_sdei.c:sdei_event_enable",
        "drivers/firmware/arm_sdei.c:_local_event_enable",
        "drivers/firmware/arm_sdei.c:sdei_platform_reset",
        "drivers/firmware/arm_sdei.c:_ipi_private_reset",
        "drivers/firmware/arm_sdei.c:sdei_unmask_local_cpu",
        "drivers/firmware/arm_sdei.c:sdei_mask_local_cpu",
        "drivers/firmware/arm_sdei.c:sdei_api_event_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501474536,
      "name": "invoke_sdei_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int invoke_sdei_fn(long unsigned int function_id, long unsigned int arg0, long unsigned int arg1, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, u64 * result)
```
</details>
</li>
</ul>
