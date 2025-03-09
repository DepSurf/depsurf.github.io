# Struct: <code>trace_event_raw_pstate_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
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
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
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
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct trace_event_raw_pstate_sample {
    struct trace_entry ent;
    u32 core_busy;
    u32 scaled_busy;
    u32 from;
    u32 to;
    u64 mperf;
    u64 aperf;
    u64 tsc;
    u32 freq;
    u32 io_boost;
    char[0] __data;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 io_boost</code>
</li>
</ul>
</details>
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
