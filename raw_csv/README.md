- **Monitoring data description** 

  Data from field monitoring surveys at **plot-visit (pv_\*), plot (p_\*), and farmer (f_\*)** levels AND monitoring qualitative /tracking data from **2 requests (r1_\* and r2_\*)** used for compliance

  Burning indicators: 

  **pv_burnt** (main burning) =1 if - Loose straw shows signs of burning (OR) loose straw visible over standing stubble shows signs of burning (OR) standing stubble shows signs of burning (OR) loose straw collected on one side of the plot shows signs or burning (OR) burnt straw/stubble visible on the plot (OR) some paddy straw stem appear burnt.

  **pv_brunt_alt** (alternate burning) = 1 if one or more of following: ash visible on soil, wet ash visible on soil, ash floating on soil, burnt grass on boundaries, trees show signs of burning

  **pv_burnt_any** = 1 if pv_burnt==1 or pv_burnt_alt==1

   

  Flags for no baseline match: (2 cases)

  **bl_error**: Plot is in monitoring but not in baseline plot-level. 

  Flags (plot-level) for burning values being changed/marked for discrepancies:

  **sc_burn_change_\***: Spotcheck burning value changed to monitoring value as spotcheck doesn’t show burning but monitor visit done earlier shows burning 

  **mon_burn_flag_\***: Burnt in spotcheck but not in later monitoring visits (no change made to spotcheck data)