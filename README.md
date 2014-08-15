For information on liblinear, please refer to README.liblinear

The following table shows the comparison between liblinear and liblinear\_gpu. liblinear\_gpu achieves 36x speedup compared to the original cpu implementation on the largest training set with 20k samples with dense 4k features.

<table border=0 cellpadding=0 cellspacing=0 width=661 style='border-collapse:
 collapse;table-layout:fixed;width:661pt'>
 <col width=63 style='mso-width-source:userset;mso-width-alt:2688;width:63pt'>
 <col width=75 style='mso-width-source:userset;mso-width-alt:3200;width:75pt'>
 <col width=65 style='width:65pt'>
 <col width=75 style='mso-width-source:userset;mso-width-alt:3200;width:75pt'>
 <col width=65 style='width:65pt'>
 <col width=121 style='mso-width-source:userset;mso-width-alt:5162;width:121pt'>
 <col width=82 style='mso-width-source:userset;mso-width-alt:3498;width:82pt'>
 <col width=115 style='mso-width-source:userset;mso-width-alt:4906;width:115pt'>
 <col width=103 style='mso-width-source:userset;mso-width-alt:4394;width:103pt'>
 <tr height=15 style='height:15.0pt'>
  <td height=15 class=xl65 width=63 style='height:15.0pt;width:63pt'>&nbsp;</td>
  <td colspan=2 class=xl66 width=140 style='width:140pt'>Liblinear</td>
  <td colspan=2 class=xl66 width=140 style='width:140pt'>Liblinear_GPU</td>
  <td class=xl67 width=121 style='width:121pt'>&nbsp;</td>
  <td class=xl67 width=82 style='width:82pt'>&nbsp;</td>
  <td class=xl68 width=115 style='width:115pt'>&nbsp;</td>
 </tr>
 <tr height=15 style='height:15.0pt'>
  <td height=15 class=xl69 style='height:15.0pt'>Data Point<span
  style='display:none'>s</span></td>
  <td>Reading Inp<span style='display:none'>ut</span></td>
  <td>Total Time</td>
  <td>Reading Inp<span style='display:none'>ut</span></td>
  <td>Total Time</td>
  <td>Computation Speed <span style='display:none'>Up</span></td>
  <td>Total Speed U<span style='display:none'>p</span></td>
  <td class=xl70>Data Matrix Size in <span style='display:none'>GB</span></td>
 </tr>
 <tr height=15 style='height:15.0pt'>
  <td height=15 class=xl69 align=right style='height:15.0pt'>1000</td>
  <td align=right>0.83</td>
  <td align=right>6.194</td>
  <td align=right>0.81</td>
  <td align=right>1.316</td>
  <td class=xl71 align=right>10.60079051</td>
  <td align=right>4.70668693</td>
  <td class=xl70 align=right>0.030517578</td>
 </tr>
 <tr height=15 style='height:15.0pt'>
  <td height=15 class=xl69 align=right style='height:15.0pt'>5000</td>
  <td align=right>4.11</td>
  <td align=right>73.964</td>
  <td align=right>4.05</td>
  <td align=right>7.075</td>
  <td class=xl71 align=right>23.0922314</td>
  <td align=right>10.45427562</td>
  <td class=xl70 align=right>0.152587891</td>
 </tr>
 <tr height=15 style='height:15.0pt'>
  <td height=15 class=xl69 align=right style='height:15.0pt'>10000</td>
  <td align=right>8.14</td>
  <td align=right>240.847</td>
  <td align=right>8.16</td>
  <td align=right>15.325</td>
  <td class=xl71 align=right>32.47829728</td>
  <td align=right>15.71595432</td>
  <td class=xl70 align=right>0.305175781</td>
 </tr>
 <tr height=15 style='height:15.0pt'>
  <td height=15 class=xl69 align=right style='height:15.0pt'>15000</td>
  <td align=right>12.24</td>
  <td align=right>345.174</td>
  <td align=right>12.16</td>
  <td align=right>26.416</td>
  <td class=xl71 align=right>23.35395623</td>
  <td align=right>13.06685342</td>
  <td class=xl70 align=right>0.457763672</td>
 </tr>
 <tr height=16 style='height:16.0pt'>
  <td height=16 class=xl72 align=right style='height:16.0pt'>20000</td>
  <td class=xl73 align=right>16.68</td>
  <td class=xl73 align=right>602.134</td>
  <td class=xl73 align=right>16.139999</td>
  <td class=xl73 align=right>32.096</td>
  <td class=xl74 align=right>36.69177509</td>
  <td class=xl73 align=right>18.76040628</td>
  <td class=xl75 align=right>0.610351563</td>
 </tr>
</table>

Test datasets are available at http://vision.ucsd.edu/~mohammad/liblinear_gpu/

Contact: mohammad at_sign ucsd dot edu
