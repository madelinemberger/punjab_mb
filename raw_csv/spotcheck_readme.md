**Spotchecks data description:**

Construction of burning variables:

7 types of burning measured: 

1. sc_burn_straw_stub "Straw or stubble looks burnt/partially burnt."

2. sc_burn_straw_ash "Black/grey ash on the soil surface."

3. sc_burn_resid  "Root residues or stubble/stem residues appear burnt."

4. sc_burn_stand_stub Standing stubble appears burnt from the top."

5. sc_burn_grass "Burnt grass and weeds on the plot boundaries."

6. sc_burn_trees_burnt "Burnt leaves/branches of the trees on the plot boundary."

7. sc_burn_realtime "Stubble's burning in real time."

 

**pv_brunt_any**: if any type of burning is noticed (any of the above 7)

**pv_burnt**: major burning (to match the monitoring variable used for burning and compliance

​      = (1) or (3) or (4) or (7)

**pv_burnt_alt** : alternative type of burning not deemed sufficient in monitoring 

​      = (2) or (5) or (6)

 

Type of field

**pv_paddy**: 1 if plot observed to be a paddy plot

 

Flags for burning values being changed/marked for discrepancies:

**sc_burn_change_\***: Spotcheck burning value changed to monitoring value as spotcheck doesn’t show burning but monitor visit done earlier shows burning 

**mon_burn_flag_\***: Burnt in spotcheck but not in later monitoring visits