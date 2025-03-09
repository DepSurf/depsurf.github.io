# Struct: <code>ptp_clock_info</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s32) adjphase;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s32) adjphase;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s32) adjphase;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[32] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s32) adjphase;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[32] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s32) adjphase;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *) getcycles64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) getcyclesx64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosscycles;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[32] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjphase;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *) getcycles64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) getcyclesx64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosscycles;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[32] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjphase;
    s32 (*)(struct ptp_clock_info *) getmaxphase;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *) getcycles64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) getcyclesx64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosscycles;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[32] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjphase;
    s32 (*)(struct ptp_clock_info *) getmaxphase;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *) getcycles64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) getcyclesx64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosscycles;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
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
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
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
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct ptp_clock_info {
    struct module * owner;
    char[16] name;
    s32 max_adj;
    int n_alarm;
    int n_ext_ts;
    int n_per_out;
    int n_pins;
    int pps;
    struct ptp_pin_desc * pin_config;
    int (*)(struct ptp_clock_info *, long int) adjfine;
    int (*)(struct ptp_clock_info *, s32) adjfreq;
    int (*)(struct ptp_clock_info *, s64) adjtime;
    int (*)(struct ptp_clock_info *, struct timespec64 *) gettime64;
    int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosststamp;
    int (*)(struct ptp_clock_info *, const struct timespec64 *) settime64;
    int (*)(struct ptp_clock_info *, struct ptp_clock_request *, int) enable;
    int (*)(struct ptp_clock_info *, unsigned int, enum ptp_pin_function, unsigned int) verify;
    long int (*)(struct ptp_clock_info *) do_aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) gettimex64</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct ptp_clock_info *, s32) adjphase</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char[16] name</code> ➡️ <code>char[32] name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct ptp_clock_info *, struct timespec64 *) getcycles64</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ptp_clock_info *, struct timespec64 *, struct ptp_system_timestamp *) getcyclesx64</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ptp_clock_info *, struct system_device_crosststamp *) getcrosscycles</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct ptp_clock_info *, s32) adjfreq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>s32 (*)(struct ptp_clock_info *) getmaxphase</code>
</li>
</ul>
</details>
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
