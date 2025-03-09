# Struct: <code>edid</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 blue_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
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
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
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
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 black_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct edid {
    u8[8] header;
    u8[2] mfg_id;
    u8[2] prod_code;
    u32 serial;
    u8 mfg_week;
    u8 mfg_year;
    u8 version;
    u8 revision;
    u8 input;
    u8 width_cm;
    u8 height_cm;
    u8 gamma;
    u8 features;
    u8 red_green_lo;
    u8 blue_white_lo;
    u8 red_x;
    u8 red_y;
    u8 green_x;
    u8 green_y;
    u8 blue_x;
    u8 blue_y;
    u8 white_x;
    u8 white_y;
    struct est_timings established_timings;
    struct std_timing[8] standard_timings;
    struct detailed_timing[4] detailed_timings;
    u8 extensions;
    u8 checksum;
}
```
</details>
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
