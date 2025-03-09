# Function: <code>__sp804_clocksource_and_sched_clock_init</code>

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
int __sp804_clocksource_and_sched_clock_init(void * base, const char * name, struct clk * clk, int use_sched_clock)
```

```json
{
  "name": "__sp804_clocksource_and_sched_clock_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511298540,
      "name": "__sp804_clocksource_and_sched_clock_init",
      "external": true,
      "loc": "drivers/clocksource/timer-sp804.c:68",
      "file": "drivers/clocksource/timer-sp804.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/timer-sp804.c:integrator_cp_of_init",
        "drivers/clocksource/timer-sp804.c:sp804_of_init",
        "drivers/clocksource/timer-sp804.c:sp804_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511298540,
      "name": "__sp804_clocksource_and_sched_clock_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int __sp804_clocksource_and_sched_clock_init(void * base, const char * name, struct clk * clk, int use_sched_clock)
```

```json
{
  "name": "__sp804_clocksource_and_sched_clock_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243957160,
      "name": "__sp804_clocksource_and_sched_clock_init",
      "external": true,
      "loc": "drivers/clocksource/timer-sp804.c:68",
      "file": "drivers/clocksource/timer-sp804.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/timer-sp804.c:integrator_cp_of_init",
        "drivers/clocksource/timer-sp804.c:sp804_of_init",
        "drivers/clocksource/timer-sp804.c:sp804_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243957160,
      "name": "__sp804_clocksource_and_sched_clock_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int __sp804_clocksource_and_sched_clock_init(void * base, const char * name, struct clk * clk, int use_sched_clock)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int __sp804_clocksource_and_sched_clock_init(void * base, const char * name, struct clk * clk, int use_sched_clock)
```
</details>
</li>
</ul>
