# nyc-trees

 ## Contributors: Hoang Minh Nguyen
 
 ## Description
    
  
   ### Usage: file: 'data_100000.csv' of Newyork City. Prepare data for model ML.
   ### Cleaning data base:
       1. drop columns :['the_geom','state','boroname']
       2. read total_nan_values=34945
       3. df.dropna(how='all')
       4. drop duplicated 
       5. replace ' ' by np.nan
       6. convert date_time
       7. "strip" and "lower_case" in the columns:
                        ['curb_loc',
                        'status',
                        'health',
                        'spc_latin',
                        'spc_common',
                        'steward',
                        'guards',
                        'sidewalk',
                        'user_type',
                        'problems',
                        'root_stone',
                        'root_grate',
                        'root_other',
                        'trnk_wire',
                        'trnk_light',
                        'trnk_other',
                        'brnch_ligh',
                        'brnch_shoe',
                        'brnch_othe',
                        'address',
                        'zip_city']
                       
        8. all column change from bool to int:
                       ['root_stone',
                      'root_grate',
                      'root_other',
                      'trnk_wire',
                      'trnk_light',
                      'trnk_other',
                      'brnch_ligh',
                      'brnch_shoe',
                      'brnch_othe']
        9. observe values "Nan" and make conclusion wat to do.
       10. file output after cleaning:  'data_100000_clean.csv'

