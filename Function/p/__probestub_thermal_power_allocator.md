# Function: <code>__probestub_thermal_power_allocator</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __probestub_thermal_power_allocator(void * __data, struct thermal_zone_device * tz, u32 * req_power, u32 total_req_power, u32 * granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp)
```

```json
{
  "name": "__probestub_thermal_power_allocator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592801680,
      "name": "__probestub_thermal_power_allocator",
      "external": true,
      "loc": "drivers/thermal/thermal_trace_ipa.h:10",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592801680,
      "name": "__probestub_thermal_power_allocator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void __probestub_thermal_power_allocator(void * __data, struct thermal_zone_device * tz, u32 total_req_power, u32 total_granted_power, int num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp)
```

```json
{
  "name": "__probestub_thermal_power_allocator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593549744,
      "name": "__probestub_thermal_power_allocator",
      "external": true,
      "loc": "drivers/thermal/thermal_trace_ipa.h:10",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593549744,
      "name": "__probestub_thermal_power_allocator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void __probestub_thermal_power_allocator(void * __data, struct thermal_zone_device * tz, u32 * req_power, u32 total_req_power, u32 * granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 * req_power</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * granted_power</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, tz, req_power, total_req_power, granted_power, total_granted_power, num_actors, power_range, max_allocatable_power, current_temp, delta_temp</code> ➡️ <code>__data, tz, total_req_power, total_granted_power, num_actors, power_range, max_allocatable_power, current_temp, delta_temp</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t num_actors</code> ➡️ <code>int num_actors</code>
</li>
</ul>
</details>
</li>
</ul>
