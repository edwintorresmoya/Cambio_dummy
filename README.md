# Cambio_dummy

multi_juan_table_1_copia = multi_juan_table_1

for(i in 1:nrow(multi_juan_table_1)){ 
    for(j in 3:ncol(multi_juan_table_1)){
        multi_juan_table_1_copia[i, j] = ifelse(multi_juan_table_1[i,j]>0, 1, 0)
}}
