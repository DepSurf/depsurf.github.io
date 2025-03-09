# Function: <code>perf_event_release_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420560,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:3835",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_disable",
        "kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420560,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494720,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4088",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_disable",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494720,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558176,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4185",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:watchdog_nmi_disable",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558176,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580588784,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4272",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:watchdog_nmi_disable",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588784,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580668736,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4206",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580668736,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800400,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4544",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800400,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866960,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4545",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866960,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963776,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4579",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963776,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581017936,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017936,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197632,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4902",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197632,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581239600,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4981",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239600,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 971
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
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256192,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:5065",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256192,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505824,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:5171",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505824,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847920,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:5069",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847920,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582273856,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:5284",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582273856,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 683
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
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582474720,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:5284",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_perf.c:watchdog_hardlockup_probe",
        "kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582474720,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 673
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
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582643424,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:5333",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_perf.c:watchdog_hardlockup_probe",
        "kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643424,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 673
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492370928,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/pmu.c:kvm_pmu_release_perf_event",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492370928,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226255864,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226255864,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285625808,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285625808,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272479060,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272479060,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580986784,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986784,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932992,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932992,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977984,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977984,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int perf_event_release_kernel(struct perf_event * event)
```

```json
{
  "name": "perf_event_release_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038800,
      "name": "perf_event_release_kernel",
      "external": true,
      "loc": "kernel/events/core.c:4674",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_init",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup",
        "kernel/events/core.c:perf_release",
        "kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038800,
      "name": "perf_event_release_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
