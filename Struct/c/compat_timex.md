# Struct: <code>compat_timex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_timex {
    compat_uint_t modes;
    compat_long_t offset;
    compat_long_t freq;
    compat_long_t maxerror;
    compat_long_t esterror;
    compat_int_t status;
    compat_long_t constant;
    compat_long_t precision;
    compat_long_t tolerance;
    struct compat_timeval time;
    compat_long_t tick;
    compat_long_t ppsfreq;
    compat_long_t jitter;
    compat_int_t shift;
    compat_long_t stabil;
    compat_long_t jitcnt;
    compat_long_t calcnt;
    compat_long_t errcnt;
    compat_long_t stbcnt;
    compat_int_t tai;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct compat_timex {
    compat_uint_t modes;
    compat_long_t offset;
    compat_long_t freq;
    compat_long_t maxerror;
    compat_long_t esterror;
    compat_int_t status;
    compat_long_t constant;
    compat_long_t precision;
    compat_long_t tolerance;
    struct compat_timeval time;
    compat_long_t tick;
    compat_long_t ppsfreq;
    compat_long_t jitter;
    compat_int_t shift;
    compat_long_t stabil;
    compat_long_t jitcnt;
    compat_long_t calcnt;
    compat_long_t errcnt;
    compat_long_t stbcnt;
    compat_int_t tai;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_timex {
    compat_uint_t modes;
    compat_long_t offset;
    compat_long_t freq;
    compat_long_t maxerror;
    compat_long_t esterror;
    compat_int_t status;
    compat_long_t constant;
    compat_long_t precision;
    compat_long_t tolerance;
    struct compat_timeval time;
    compat_long_t tick;
    compat_long_t ppsfreq;
    compat_long_t jitter;
    compat_int_t shift;
    compat_long_t stabil;
    compat_long_t jitcnt;
    compat_long_t calcnt;
    compat_long_t errcnt;
    compat_long_t stbcnt;
    compat_int_t tai;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_timex {
    compat_uint_t modes;
    compat_long_t offset;
    compat_long_t freq;
    compat_long_t maxerror;
    compat_long_t esterror;
    compat_int_t status;
    compat_long_t constant;
    compat_long_t precision;
    compat_long_t tolerance;
    struct compat_timeval time;
    compat_long_t tick;
    compat_long_t ppsfreq;
    compat_long_t jitter;
    compat_int_t shift;
    compat_long_t stabil;
    compat_long_t jitcnt;
    compat_long_t calcnt;
    compat_long_t errcnt;
    compat_long_t stbcnt;
    compat_int_t tai;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_timex {
    compat_uint_t modes;
    compat_long_t offset;
    compat_long_t freq;
    compat_long_t maxerror;
    compat_long_t esterror;
    compat_int_t status;
    compat_long_t constant;
    compat_long_t precision;
    compat_long_t tolerance;
    struct compat_timeval time;
    compat_long_t tick;
    compat_long_t ppsfreq;
    compat_long_t jitter;
    compat_int_t shift;
    compat_long_t stabil;
    compat_long_t jitcnt;
    compat_long_t calcnt;
    compat_long_t errcnt;
    compat_long_t stbcnt;
    compat_int_t tai;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct compat_timex {
    compat_uint_t modes;
    compat_long_t offset;
    compat_long_t freq;
    compat_long_t maxerror;
    compat_long_t esterror;
    compat_int_t status;
    compat_long_t constant;
    compat_long_t precision;
    compat_long_t tolerance;
    struct compat_timeval time;
    compat_long_t tick;
    compat_long_t ppsfreq;
    compat_long_t jitter;
    compat_int_t shift;
    compat_long_t stabil;
    compat_long_t jitcnt;
    compat_long_t calcnt;
    compat_long_t errcnt;
    compat_long_t stbcnt;
    compat_int_t tai;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct compat_timex {
    compat_uint_t modes;
    compat_long_t offset;
    compat_long_t freq;
    compat_long_t maxerror;
    compat_long_t esterror;
    compat_int_t status;
    compat_long_t constant;
    compat_long_t precision;
    compat_long_t tolerance;
    struct old_timeval32 time;
    compat_long_t tick;
    compat_long_t ppsfreq;
    compat_long_t jitter;
    compat_int_t shift;
    compat_long_t stabil;
    compat_long_t jitcnt;
    compat_long_t calcnt;
    compat_long_t errcnt;
    compat_long_t stbcnt;
    compat_int_t tai;
}
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct compat_timeval time</code> ➡️ <code>struct old_timeval32 time</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct compat_timex {
    compat_uint_t modes;
    compat_long_t offset;
    compat_long_t freq;
    compat_long_t maxerror;
    compat_long_t esterror;
    compat_int_t status;
    compat_long_t constant;
    compat_long_t precision;
    compat_long_t tolerance;
    struct old_timeval32 time;
    compat_long_t tick;
    compat_long_t ppsfreq;
    compat_long_t jitter;
    compat_int_t shift;
    compat_long_t stabil;
    compat_long_t jitcnt;
    compat_long_t calcnt;
    compat_long_t errcnt;
    compat_long_t stbcnt;
    compat_int_t tai;
}
```
</details>
</li>
</ul>
