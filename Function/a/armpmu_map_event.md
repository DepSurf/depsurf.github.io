# Function: <code>armpmu_map_event</code>

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
int armpmu_map_event(struct perf_event * event, const unsigned int[10] * event_map, const unsigned int[42] * cache_map, u32 raw_event_mask)
```

```json
{
  "name": "armpmu_map_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501775456,
      "name": "armpmu_map_event",
      "external": true,
      "loc": "drivers/perf/arm_pmu.c:94",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501775456,
      "name": "armpmu_map_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int armpmu_map_event(struct perf_event * event, const unsigned int[10] * event_map, const unsigned int[42] * cache_map, u32 raw_event_mask)
```

```json
{
  "name": "armpmu_map_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234325132,
      "name": "armpmu_map_event",
      "external": true,
      "loc": "drivers/perf/arm_pmu.c:94",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/perf_event_v7.c:scorpion_map_event",
        "arch/arm/kernel/perf_event_v7.c:krait_map_event_no_branch",
        "arch/arm/kernel/perf_event_v7.c:krait_map_event",
        "arch/arm/kernel/perf_event_v7.c:armv7_a12_map_event",
        "arch/arm/kernel/perf_event_v7.c:armv7_a7_map_event",
        "arch/arm/kernel/perf_event_v7.c:armv7_a15_map_event",
        "arch/arm/kernel/perf_event_v7.c:armv7_a5_map_event",
        "arch/arm/kernel/perf_event_v7.c:armv7_a9_map_event",
        "arch/arm/kernel/perf_event_v7.c:armv7_a8_map_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234325132,
      "name": "armpmu_map_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
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
int armpmu_map_event(struct perf_event * event, const unsigned int[10] * event_map, const unsigned int[42] * cache_map, u32 raw_event_mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int armpmu_map_event(struct perf_event * event, const unsigned int[10] * event_map, const unsigned int[42] * cache_map, u32 raw_event_mask)
```
</details>
</li>
</ul>
