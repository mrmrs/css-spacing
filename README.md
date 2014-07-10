# CSS SPACING

  Mobile-first classes for css-spacing.
  Set the desired css-spacing on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-spacing
```
or download the css on github and include in your project.

## File Size


## The Code
```
   An eight step powers of two scale ranging from 0 to 16rem.

   Legend:

   p = padding
   m = margin

   a = all
   h = horizontal
   v = vertical
   t = top
   r = right
   b = bottom
   l = left

   n = none
   xs = extra small
   s = small
   m = medium
   l = large
   x = extra
   xl = extra large
   xxl = extra extra large

    */

.pan  {  padding: 0; }
.paxs {  padding: .25rem; }
.pas  {  padding: .5rem; }
.pam  {  padding: 1rem; }
.pal  {  padding: 2rem; }
.pax  {  padding: 4rem; }
.paxl {  padding: 8rem; }
.paxxl { padding: 16rem; }

.pln  {  padding-left: 0; }
.plxs {  padding-left: .25rem; }
.pls  {  padding-left: .5rem; }
.plm  {  padding-left: 1rem; }
.pll  {  padding-left: 2rem; }
.plx  {  padding-left: 4rem; }
.plxl {  padding-left: 8rem; }
.plxxl { padding-left: 16rem; }

.prn  {  padding-right: 0; }
.prxs {  padding-right: .25rem; }
.prs  {  padding-right: .5rem; }
.prm  {  padding-right: 1rem; }
.prl  {  padding-right: 2rem; }
.prx  {  padding-right: 4rem; }
.prxl {  padding-right: 8rem; }
.prxxl { padding-right: 16rem; }

.pbn  {  padding-bottom: 0; }
.pbxs {  padding-bottom: .25rem; }
.pbs  {  padding-bottom: .5rem; }
.pbm  {  padding-bottom: 1rem; }
.pbl  {  padding-bottom: 2rem; }
.pbx  {  padding-bottom: 4rem; }
.pbxl {  padding-bottom: 8rem; }
.pbxxl { padding-bottom: 16rem; }

.ptn  {  padding-top: 0; }
.ptxs {  padding-top: .25rem; }
.pts  {  padding-top: .5rem; }
.ptm  {  padding-top: 1rem; }
.ptl  {  padding-top: 2rem; }
.ptx  {  padding-top: 4rem; }
.ptxl {  padding-top: 8rem; }
.ptxxl { padding-top: 16rem; }

.pvn {   padding-top: 0;       padding-bottom: 0; }
.pvxs {  padding-top: .25rem;  padding-bottom: .25rem; }
.pvs {   padding-top: .5rem;   padding-bottom: .5rem; }
.pvm {   padding-top: 1rem;    padding-bottom: 1rem; }
.pvl {   padding-top: 2rem;    padding-bottom: 2rem; }
.pvx {   padding-top: 4rem;    padding-bottom: 4rem; }
.pvxl {  padding-top: 8rem;    padding-bottom: 8rem; }
.pvxxl { padding-top: 16rem;   padding-bottom: 16rem; }

.phn {   padding-left: 0;      padding-right: 0; }
.pvxs {  padding-left: .25rem; padding-right: .25rem; }
.phs {   padding-left: .5rem;  padding-right: .5rem; }
.phm {   padding-left: 1rem;   padding-right: 1rem; }
.phl {   padding-left: 2rem;   padding-right: 2rem; }
.phx {   padding-left: 4rem;   padding-right: 4rem; }
.phxl {  padding-left: 8rem;   padding-right: 8rem; }
.phxxl { padding-left: 16rem;  padding-right: 16rem; }

.man  {  margin: 0; }
.maxs {  margin: .25rem; }
.mas  {  margin: .5rem; }
.mam  {  margin: 1rem; }
.mal  {  margin: 2rem; }
.max  {  margin: 4rem; }
.maxl {  margin: 8rem; }
.maxxl { margin: 16rem; }

.mln  {  margin-left: 0; }
.mlxs {  margin-left: .25rem; }
.mls  {  margin-left: .5rem; }
.mlm  {  margin-left: 1rem; }
.mll  {  margin-left: 2rem; }
.mlx  {  margin-left: 4rem; }
.mlxl {  margin-left: 8rem; }
.mlxxl { margin-left: 16rem; }

.mrn  {  margin-right: 0; }
.mrxs {  margin-right: .25rem; }
.mrs  {  margin-right: .5rem; }
.mrm  {  margin-right: 1rem; }
.mrl  {  margin-right: 2rem; }
.mrx  {  margin-right: 4rem; }
.mrxl {  margin-right: 8rem; }
.mrxxl { margin-right: 16rem; }

.mbn  {  margin-bottom: 0; }
.mbxs {  margin-bottom: .25rem; }
.mbs  {  margin-bottom: .5rem; }
.mbm  {  margin-bottom: 1rem; }
.mbl  {  margin-bottom: 2rem; }
.mbx  {  margin-bottom: 4rem; }
.mbxl {  margin-bottom: 8rem; }
.mbxxl { margin-bottom: 16rem; }

.mtn  {  margin-top: 0; }
.mtxs {  margin-top: .25rem; }
.mts  {  margin-top: .5rem; }
.mtm  {  margin-top: 1rem; }
.mtl  {  margin-top: 2rem; }
.mtx  {  margin-top: 4rem; }
.mtxl {  margin-top: 8rem; }
.mtxxl { margin-top: 16rem; }

.mvn   { margin-top: 0;      margin-bottom: 0rem; }
.mvxs  { margin-top: .25rem; margin-bottom: .25rem; }
.mvs   { margin-top: .5rem;  margin-bottom: .5rem; }
.mvm   { margin-top: 1rem;   margin-bottom: 1rem; }
.mvl   { margin-top: 2rem;   margin-bottom: 2rem; }
.mvx   { margin-top: 4rem;   margin-bottom: 4rem; }
.mvxl  { margin-top: 8rem;   margin-bottom: 8rem; }
.mvxl  { margin-top: 16rem;   margin-bottom: 16rem; }

.mhn   {  margin-left: 0;     margin-right: 0; }
.mhs   {  margin-left: .5rem; margin-right: .5rem; }
.mhm   {  margin-left: 1rem;  margin-right: 1rem; }
.mhl   {  margin-left: 2rem;  margin-right: 2rem; }
.mhx   {  margin-left: 4rem;  margin-right: 4rem; }
.mhxl  {  margin-left: 8rem;  margin-right: 8rem; }
.mhxxl  { margin-left: 16rem; margin-right: 16rem; }

@include break(not-small) {
  .pan-ns  {  padding: 0; }
  .paxs-ns {  padding: .25rem; }
  .pas-ns  {  padding: .5rem; }
  .pam-ns  {  padding: 1rem; }
  .pal-ns  {  padding: 2rem; }
  .pax-ns  {  padding: 4rem; }
  .paxl-ns {  padding: 8rem; }
  .paxxl-ns { padding: 16rem; }

  .pln-ns  {  padding-left: 0; }
  .plxs-ns {  padding-left: .25rem; }
  .pls-ns  {  padding-left: .5rem; }
  .plm-ns  {  padding-left: 1rem; }
  .pll-ns  {  padding-left: 2rem; }
  .plx-ns  {  padding-left: 4rem; }
  .plxl-ns {  padding-left: 8rem; }
  .plxxl-ns { padding-left: 16rem; }

  .prn-ns  {  padding-right: 0; }
  .prxs-ns {  padding-right: .25rem; }
  .prs-ns  {  padding-right: .5rem; }
  .prm-ns  {  padding-right: 1rem; }
  .prl-ns  {  padding-right: 2rem; }
  .prx-ns {   padding-right: 4rem; }
  .prxl-ns {  padding-right: 8rem; }
  .prxxl-ns { padding-right: 16rem; }

  .pbn-ns  {  padding-bottom: 0; }
  .pbxs-ns {  padding-bottom: .25rem; }
  .pbs-ns  {  padding-bottom: .5rem; }
  .pbm-ns  {  padding-bottom: 1rem; }
  .pbl-ns  {  padding-bottom: 2rem; }
  .pbx-ns  {  padding-bottom: 4rem; }
  .pbxl-ns {  padding-bottom: 8rem; }
  .pbxxl-ns { padding-bottom: 16rem; }

  .ptn-ns  {  padding-top: 0; }
  .ptxs-ns {  padding-top: .25rem; }
  .pts-ns  {  padding-top: .5rem; }
  .ptm-ns  {  padding-top: 1rem; }
  .ptl-ns  {  padding-top: 2rem; }
  .ptx-ns  {  padding-top: 4rem; }
  .ptxl-ns {  padding-top: 8rem; }
  .ptxxl-ns { padding-top: 16rem; }

  .pvn-ns {   padding-top: 0;       padding-bottom: 0; }
  .pvxs-ns {  padding-top: .25rem;  padding-bottom: .25rem; }
  .pvs-ns {   padding-top: .5rem;   padding-bottom: .5rem; }
  .pvm-ns {   padding-top: 1rem;    padding-bottom: 1rem; }
  .pvl-ns {   padding-top: 2rem;    padding-bottom: 2rem; }
  .pvx-ns {   padding-top: 4rem;    padding-bottom: 4rem; }
  .pvxl-ns {  padding-top: 8rem;    padding-bottom: 8rem; }
  .pvxxl-ns { padding-top: 16rem;   padding-bottom: 16rem; }

  .phn-ns {   padding-left: 0;      padding-right: 0; }
  .pvxs-ns {  padding-left: .25rem; padding-right: .25rem; }
  .phs-ns {   padding-left: .5rem;  padding-right: .5rem; }
  .phm-ns {   padding-left: 1rem;   padding-right: 1rem; }
  .phl-ns {   padding-left: 2rem;   padding-right: 2rem; }
  .phx-ns {   padding-left: 4rem;   padding-right: 4rem; }
  .phxl-ns {  padding-left: 8rem;   padding-right: 8rem; }
  .phxxl-ns { padding-left: 16rem;  padding-right: 16rem; }

  .man-ns  {  margin: 0; }
  .maxs-ns {  margin: .25rem; }
  .mas-ns  {  margin: .5rem; }
  .mam-ns  {  margin: 1rem; }
  .mal-ns  {  margin: 2rem; }
  .max-ns  {  margin: 4rem; }
  .maxl-ns {  margin: 8rem; }
  .maxxl-ns { margin: 16rem; }

  .mln-ns  {  margin-left: 0; }
  .mlxs-ns {  margin-left: .25rem; }
  .mls-ns  {  margin-left: .5rem; }
  .mlm-ns  {  margin-left: 1rem; }
  .mll-ns  {  margin-left: 2rem; }
  .mlx-ns  {  margin-left: 4rem; }
  .mlxl-ns {  margin-left: 8rem; }
  .mlxxl-ns { margin-left: 16rem; }

  .mrn-ns  {  margin-right: 0; }
  .mrxs-ns {  margin-right: .25rem; }
  .mrs-ns  {  margin-right: .5rem; }
  .mrm-ns  {  margin-right: 1rem; }
  .mrl-ns  {  margin-right: 2rem; }
  .mrx-ns  {  margin-right: 4rem; }
  .mrxl-ns {  margin-right: 8rem; }
  .mrxxl-ns { margin-right: 16rem; }

  .mbn-ns  {  margin-bottom: 0; }
  .mbxs-ns {  margin-bottom: .25rem; }
  .mbs-ns  {  margin-bottom: .5rem; }
  .mbm-ns  {  margin-bottom: 1rem; }
  .mbl-ns  {  margin-bottom: 2rem; }
  .mbx-ns  {  margin-bottom: 4rem; }
  .mbxl-ns {  margin-bottom: 8rem; }
  .mbxxl-ns { margin-bottom: 16rem; }

  .mtn-ns  {  margin-top: 0; }
  .mtxs-ns {  margin-top: .25rem; }
  .mts-ns  {  margin-top: .5rem; }
  .mtm-ns  {  margin-top: 1rem; }
  .mtl-ns  {  margin-top: 2rem; }
  .mtx-ns  {  margin-top: 4rem; }
  .mtxl-ns {  margin-top: 8rem; }
  .mtxxl-ns { margin-top: 16rem; }

  .mvn-ns   {  margin-top: 0;      margin-bottom: 0rem; }
  .mvxs-ns  {  margin-top: .25rem; margin-bottom: .25rem; }
  .mvs-ns   {  margin-top: .5rem;  margin-bottom: .5rem; }
  .mvm-ns   {  margin-top: 1rem;   margin-bottom: 1rem; }
  .mvl-ns   {  margin-top: 2rem;   margin-bottom: 2rem; }
  .mvx-ns   {  margin-top: 4rem;   margin-bottom: 4rem; }
  .mvxl-ns  {  margin-top: 8rem;   margin-bottom: 8rem; }
  .mvxxl-ns  { margin-top: 16rem;  margin-bottom: 16rem; }

   .mhn-ns   {  margin-left: 0;     margin-right: 0; }
   .mhs-ns   {  margin-left: .5rem; margin-right: .5rem; }
   .mhm-ns   {  margin-left: 1rem;  margin-right: 1rem; }
   .mhl-ns   {  margin-left: 2rem;  margin-right: 2rem; }
   .mhx-ns   {  margin-left: 4rem;  margin-right: 4rem; }
   .mhxl-ns  {  margin-left: 8rem;  margin-right: 8rem; }
   .mhxxl-ns  { margin-left: 16rem; margin-right: 16rem; }

}

@include break(medium) {
  .pan-m  {  padding: 0; }
  .paxs-m {  padding: .25rem; }
  .pas-m  {  padding: .5rem; }
  .pam-m  {  padding: 1rem; }
  .pal-m  {  padding: 2rem; }
  .pax-m  {  padding: 4rem; }
  .paxl-m {  padding: 8rem; }
  .paxxl-m { padding: 16rem; }

  .pln-m  {  padding-left: 0; }
  .plxs-m {  padding-left: .25rem; }
  .pls-m  {  padding-left: .5rem; }
  .plm-m  {  padding-left: 1rem; }
  .pll-m  {  padding-left: 2rem; }
  .plx-m  {  padding-left: 4rem; }
  .plxl-m {  padding-left: 8rem; }
  .plxxl-m { padding-left: 16rem; }

  .prn-m  {  padding-right: 0; }
  .prxs-m {  padding-right: .25rem; }
  .prs-m  {  padding-right: .5rem; }
  .prm-m  {  padding-right: 1rem; }
  .prl-m  {  padding-right: 2rem; }
  .prx-m  {  padding-right: 4rem; }
  .prxl-m {  padding-right: 8rem; }
  .prxxl-m { padding-right: 16rem; }

  .pbn-m  {  padding-bottom: 0; }
  .pbxs-m {  padding-bottom: .25rem; }
  .pbs-m  {  padding-bottom: .5rem; }
  .pbm-m  {  padding-bottom: 1rem; }
  .pbl-m  {  padding-bottom: 2rem; }
  .pbx-m  {  padding-bottom: 4rem; }
  .pbxl-m {  padding-bottom: 8rem; }
  .pbxxl-m { padding-bottom: 16rem; }

  .ptn-m  {  padding-top: 0; }
  .ptxs-m {  padding-top: .25rem; }
  .pts-m  {  padding-top: .5rem; }
  .ptm-m  {  padding-top: 1rem; }
  .ptl-m  {  padding-top: 2rem; }
  .ptx-m  {  padding-top: 4rem; }
  .ptxl-m {  padding-top: 8rem; }
  .ptxxl-m { padding-top: 16rem; }

  .pvn-m {   padding-top: 0;       padding-bottom: 0; }
  .pvxs-m {  padding-top: .25rem;  padding-bottom: .25rem; }
  .pvs-m {   padding-top: .5rem;   padding-bottom: .5rem; }
  .pvm-m {   padding-top: 1rem;    padding-bottom: 1rem; }
  .pvl-m {   padding-top: 2rem;    padding-bottom: 2rem; }
  .pvx-m {   padding-top: 4rem;    padding-bottom: 4rem; }
  .pvxl-m {  padding-top: 8rem;    padding-bottom: 8rem; }
  .pvxxl-m { padding-top: 16rem;   padding-bottom: 16rem; }

  .phn-m {   padding-left: 0;      padding-right: 0; }
  .pvxs-m {  padding-left: .25rem; padding-right: .25rem; }
  .phs-m {   padding-left: .5rem;  padding-right: .5rem; }
  .phm-m {   padding-left: 1rem;   padding-right: 1rem; }
  .phl-m {   padding-left: 2rem;   padding-right: 2rem; }
  .phx-m {   padding-left: 4rem;   padding-right: 4rem; }
  .phxl-m {  padding-left: 8rem;   padding-right: 8rem; }
  .phxxl-m { padding-left: 16rem;  padding-right: 16rem; }

  .man-m  {  margin: 0; }
  .maxs-m {  margin: .25rem; }
  .mas-m  {  margin: .5rem; }
  .mam-m  {  margin: 1rem; }
  .mal-m  {  margin: 2rem; }
  .max-m  {  margin: 4rem; }
  .maxl-m {  margin: 8rem; }
  .maxxl-m { margin: 16rem; }

  .mln-m  {  margin-left: 0; }
  .mlxs-m {  margin-left: .25rem; }
  .mls-m  {  margin-left: .5rem; }
  .mlm-m  {  margin-left: 1rem; }
  .mll-m  {  margin-left: 2rem; }
  .mlx-m  {  margin-left: 4rem; }
  .mlxl-m {  margin-left: 8rem; }
  .mlxxl-m { margin-left: 16rem; }

  .mrn-m  {  margin-right: 0; }
  .mrxs-m {  margin-right: .25rem; }
  .mrs-m  {  margin-right: .5rem; }
  .mrm-m  {  margin-right: 1rem; }
  .mrl-m  {  margin-right: 2rem; }
  .mrx-m  {  margin-right: 4rem; }
  .mrxl-m {  margin-right: 8rem; }
  .mrxxl-m { margin-right: 16rem; }

  .mbn-m  {  margin-bottom: 0; }
  .mbxs-m {  margin-bottom: .25rem; }
  .mbs-m  {  margin-bottom: .5rem; }
  .mbm-m  {  margin-bottom: 1rem; }
  .mbl-m  {  margin-bottom: 2rem; }
  .mbx-m  {  margin-bottom: 4rem; }
  .mbxl-m {  margin-bottom: 8rem; }
  .mbxxl-m { margin-bottom: 16rem; }

  .mtn-m  {  margin-top: 0; }
  .mtxs-m {  margin-top: .25rem; }
  .mts-m  {  margin-top: .5rem; }
  .mtm-m  {  margin-top: 1rem; }
  .mtl-m  {  margin-top: 2rem; }
  .mtx-m  {  margin-top: 4rem; }
  .mtxl-m {  margin-top: 8rem; }
  .mtxxl-m { margin-top: 16rem; }

  .mvn-m {   margin-top: 0;      margin-bottom: 0rem; }
  .mvxs-m {  margin-top: .25rem; margin-bottom: .25rem; }
  .mvs-m {   margin-top: .5rem;  margin-bottom: .5rem; }
  .mvm-m {   margin-top: 1rem;   margin-bottom: 1rem; }
  .mvl-m {   margin-top: 2rem;   margin-bottom: 2rem; }
  .mvx-m {   margin-top: 4rem;   margin-bottom: 4rem; }
  .mvxl-m {  margin-top: 8rem;   margin-bottom: 8rem; }
  .mvxxl-m { margin-top: 16rem;  margin-bottom: 16rem; }

  .mhn-m {  margin-left: 0;      margin-right: 0; }
  .mhxs-m { margin-left: .25rem; margin-right: .25rem; }
  .mhs-m {  margin-left: .5rem;  margin-right: .5rem; }
  .mhm-m {  margin-left: 1rem;   margin-right: 1rem; }
  .mhl-m {  margin-left: 2rem;   margin-right: 2rem; }
  .mhx-m {  margin-left: 4rem;   margin-right: 4rem; }
  .mhxl {   margin-left: 8rem;   margin-right: 8rem; }
  .mhxxl {  margin-left: 16rem;  margin-right: 16rem; }

}

@include break(large) {
  .pan-l  {  padding: 0; }
  .paxs-l {  padding: .25rem; }
  .pas-l  {  padding: .5rem; }
  .pam-l  {  padding: 1rem; }
  .pal-l  {  padding: 2rem; }
  .pax-l  {  padding: 4rem; }
  .paxl-l {  padding: 8rem; }
  .paxxl-l { padding: 16rem; }

  .pln-l  {  padding-left: 0; }
  .plxs-l {  padding-left: .25rem; }
  .pls-l  {  padding-left: .5rem; }
  .plm-l  {  padding-left: 1rem; }
  .pll-l  {  padding-left: 2rem; }
  .plx-l  {  padding-left: 4rem; }
  .plxl-l {  padding-left: 8rem; }
  .plxxl-l { padding-left: 16rem; }

  .prn-l  {  padding-right: 0; }
  .prxs-l {  padding-right: .25rem; }
  .prs-l  {  padding-right: .5rem; }
  .prm-l  {  padding-right: 1rem; }
  .prl-l  {  padding-right: 2rem; }
  .prx-l  {  padding-right: 4rem; }
  .prxl-l {  padding-right: 8rem; }
  .prxxl-l { padding-right: 16rem; }

  .pbn-l  {  padding-bottom: 0; }
  .pbxs-l {  padding-bottom: .25rem; }
  .pbs-l  {  padding-bottom: .5rem; }
  .pbm-l  {  padding-bottom: 1rem; }
  .pbl-l  {  padding-bottom: 2rem; }
  .pbx-l  {  padding-bottom: 4rem; }
  .pbxl-l {  padding-bottom: 8rem; }
  .pbxxl-l { padding-bottom: 16rem; }

  .ptn-l  {  padding-top: 0; }
  .ptxs-l {  padding-top: .25rem; }
  .pts-l  {  padding-top: .5rem; }
  .ptm-l  {  padding-top: 1rem; }
  .ptl-l  {  padding-top: 2rem; }
  .ptx-l  {  padding-top: 4rem; }
  .ptxl-l {  padding-top: 8rem; }
  .ptxxl-l { padding-top: 16rem; }

  .pvn-l {   padding-top: 0;       padding-bottom: 0; }
  .pvxs-l {  padding-top: .25rem;  padding-bottom: .25rem; }
  .pvs-l {   padding-top: .5rem;   padding-bottom: .5rem; }
  .pvm-l {   padding-top: 1rem;    padding-bottom: 1rem; }
  .pvl-l {   padding-top: 2rem;    padding-bottom: 2rem; }
  .pvx-l {   padding-top: 4rem;    padding-bottom: 4rem; }
  .pvxl-l {  padding-top: 8rem;    padding-bottom: 8rem; }
  .pvxxl-l { padding-top: 16rem;   padding-bottom: 16rem; }

  .phn-l {   padding-left: 0;      padding-right: 0; }
  .pvxs-l {  padding-left: .25rem; padding-right: .25rem; }
  .phs-l {   padding-left: .5rem;  padding-right: .5rem; }
  .phm-l {   padding-left: 1rem;   padding-right: 1rem; }
  .phl-l {   padding-left: 2rem;   padding-right: 2rem; }
  .phx-l {   padding-left: 4rem;   padding-right: 4rem; }
  .phxl-l {  padding-left: 8rem;   padding-right: 8rem; }
  .phxxl-l { padding-left: 16rem;  padding-right: 16rem; }

  .man-l  {  margin: 0; }
  .maxs-l {  margin: .25rem; }
  .mas-l  {  margin: .5rem; }
  .mam-l  {  margin: 1rem; }
  .mal-l  {  margin: 2rem; }
  .max-l  {  margin: 4rem; }
  .maxl-l {  margin: 8rem; }
  .maxxl-l { margin: 16rem; }

  .mln-l  {  margin-left: 0; }
  .mlxs-l {  margin-left: .25rem; }
  .mls-l  {  margin-left: .5rem; }
  .mlm-l  {  margin-left: 1rem; }
  .mll-l  {  margin-left: 2rem; }
  .mlx-l  {  margin-left: 4rem; }
  .mlxl-l {  margin-left: 8rem; }
  .mlxxl-l { margin-left: 16rem; }

  .mrn-l  {  margin-right: 0; }
  .mrxs-l {  margin-right: .25rem; }
  .mrs-l  {  margin-right: .5rem; }
  .mrm-l  {  margin-right: 1rem; }
  .mrl-l  {  margin-right: 2rem; }
  .mrx-l  {  margin-right: 4rem; }
  .mrxl-l {  margin-right: 8rem; }
  .mrxxl-l { margin-right: 16rem; }

  .mbn-l  {  margin-bottom: 0; }
  .mbxs-l {  margin-bottom: .25rem; }
  .mbs-l  {  margin-bottom: .5rem; }
  .mbm-l  {  margin-bottom: 1rem; }
  .mbl-l  {  margin-bottom: 2rem; }
  .mbx-l  {  margin-bottom: 4rem; }
  .mbxl-l {  margin-bottom: 8rem; }
  .mbxxl-l { margin-bottom: 16rem; }

  .mtn-l  {  margin-top: 0; }
  .mtxs-l {  margin-top: .25rem; }
  .mts-l  {  margin-top: .5rem; }
  .mtm-l  {  margin-top: 1rem; }
  .mtl-l  {  margin-top: 2rem; }
  .mtx-l  {  margin-top: 4rem; }
  .mtxl-l {  margin-top: 8rem; }
  .mtxxl-l { margin-top: 16rem; }

  .mvn-l {   margin-top: 0;      margin-bottom: 0rem; }
  .mvxs-l {  margin-top: .25rem; margin-bottom: .25rem; }
  .mvs-l {   margin-top: .5rem;  margin-bottom: .5rem; }
  .mvm-l {   margin-top: 1rem;   margin-bottom: 1rem; }
  .mvl-l {   margin-top: 2rem;   margin-bottom: 2rem; }
  .mvx-l {   margin-top: 4rem;   margin-bottom: 4rem; }
  .mvxl-l {  margin-top: 8rem;   margin-bottom: 8rem; }
  .mvxxl-l { margin-top: 16rem;  margin-bottom: 16rem; }

  .mhn-l {   margin-left: 0;      margin-right: 0; }
  .mhxs-l {  margin-left: .25rem; margin-right: .25rem; }
  .mhs-l {   margin-left: .5rem;  margin-right: .5rem; }
  .mhm-l {   margin-left: 1rem;   margin-right: 1rem; }
  .mhl-l {   margin-left: 2rem;   margin-right: 2rem; }
  .mhx-l {   margin-left: 4rem;   margin-right: 4rem; }
  .mhxl-l {  margin-left: 8rem;   margin-right: 8rem; }
  .mhxxl-l { margin-left: 16rem;  margin-right: 16rem; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

