##################################
add_subdirectory(dfadd)
add_subdirectory(dfmul)
add_subdirectory(dfdiv)
add_subdirectory(dfsin)

##################################
#Add the benchmark of encryption 

add_subdirectory(sha)
add_subdirectory(aes)
add_subdirectory(adpcm)

##################################
#Add the benchmark of other categories

#add_subdirectory(gsm)
add_subdirectory(mips)

##################################
#Huge design gol last
add_subdirectory(blowfish)
add_subdirectory(jpeg)

# This is actually the first run
add_subdirectory(motion)
