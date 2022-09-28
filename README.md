# EntroCR: An intelligent recognition method of chromosome rearrangement patterns based on information entropy
###### This procedure mainly includes three steps: get the comparison unit, output combination picture, output the highest similarity of the three combinations
## The first step
### Input len file and gff file of two species, blast file, csv file obtained by WGDI
### Output the KS dotplot of each comparison unit
#### with open('total.conf', 'w') as f:           #For specific settings, please refer to the WGDI program description
#### if __name__ == "__main__":           #It is recommended to fill in the abbreviation of the name of the experimental species, where the number "range" is 1 to the number of chromosomes of the species
## The second step
### Input the KS dotplot of each comparison unit and len file
### Output combinatorial graph after binarization
#### single = 'E:/PycharmProjects/shiyan-quan-Bra'  #Location of the KS dotplot of each comparison unit and location of len files
## The third step
### Input Enter the combination diagram, the single image in the upper left corner of the combination diagram, the CSV file of the standard diagram, and the rearrangement category
### Output the names and values of the three most similar combination graph
#### biaozhun = biaozhun[biaozhun["id"]==4] #the rearrangement category
#### picpath = r'E:\PycharmProjects\shiyan-Osa'   #The location where the composite diagram is stored
#### lastfile = r'E:\PycharmProjects\shiyan-Osa\resultlast.csv'  #Output file storage location
