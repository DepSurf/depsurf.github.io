# Struct: <code>sfp_eeprom_base</code>

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
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
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
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
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
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
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
struct sfp_eeprom_base {
    u8 phys_id;
    u8 phys_ext_id;
    u8 connector;
    u8 if_1x_copper_passive;
    u8 if_1x_copper_active;
    u8 if_1x_lx;
    u8 if_1x_sx;
    u8 e10g_base_sr;
    u8 e10g_base_lr;
    u8 e10g_base_lrm;
    u8 e10g_base_er;
    u8 sonet_oc3_short_reach;
    u8 sonet_oc3_smf_intermediate_reach;
    u8 sonet_oc3_smf_long_reach;
    u8 unallocated_5_3;
    u8 sonet_oc12_short_reach;
    u8 sonet_oc12_smf_intermediate_reach;
    u8 sonet_oc12_smf_long_reach;
    u8 unallocated_5_7;
    u8 sonet_oc48_short_reach;
    u8 sonet_oc48_intermediate_reach;
    u8 sonet_oc48_long_reach;
    u8 sonet_reach_bit2;
    u8 sonet_reach_bit1;
    u8 sonet_oc192_short_reach;
    u8 escon_smf_1310_laser;
    u8 escon_mmf_1310_led;
    u8 e1000_base_sx;
    u8 e1000_base_lx;
    u8 e1000_base_cx;
    u8 e1000_base_t;
    u8 e100_base_lx;
    u8 e100_base_fx;
    u8 e_base_bx10;
    u8 e_base_px;
    u8 fc_tech_electrical_inter_enclosure;
    u8 fc_tech_lc;
    u8 fc_tech_sa;
    u8 fc_ll_m;
    u8 fc_ll_l;
    u8 fc_ll_i;
    u8 fc_ll_s;
    u8 fc_ll_v;
    u8 unallocated_8_0;
    u8 unallocated_8_1;
    u8 sfp_ct_passive;
    u8 sfp_ct_active;
    u8 fc_tech_ll;
    u8 fc_tech_sl;
    u8 fc_tech_sn;
    u8 fc_tech_electrical_intra_enclosure;
    u8 fc_media_sm;
    u8 unallocated_9_1;
    u8 fc_media_m5;
    u8 fc_media_m6;
    u8 fc_media_tv;
    u8 fc_media_mi;
    u8 fc_media_tp;
    u8 fc_media_tw;
    u8 fc_speed_100;
    u8 unallocated_10_1;
    u8 fc_speed_200;
    u8 fc_speed_3200;
    u8 fc_speed_400;
    u8 fc_speed_1600;
    u8 fc_speed_800;
    u8 fc_speed_1200;
    u8 encoding;
    u8 br_nominal;
    u8 rate_id;
    u8[6] link_len;
    char[16] vendor_name;
    u8 extended_cc;
    char[3] vendor_oui;
    char[16] vendor_pn;
    char[4] vendor_rev;
    __be16 optical_wavelength;
    __be16 cable_compliance;
    struct (anon) passive;
    struct (anon) active;
    u8 reserved62;
    u8 cc_base;
}
```
</details>
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
