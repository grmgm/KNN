# KNN

## Overview. 

Developed own KNN algorithm with Hamming distance and cross validation.  

For KNN algorithm development, use the `MushroomDataset.csv` file provided.    

The classification problem here is to predict what type of mushroom it is (edible vs poisonous) using the attributes below.  

Then the KNN algorithm is compared with Naive Bayes classification in sklearn package.

For the comparison, use `GlassDataset.csv` file provided. 

The classification problem here is to predict what type of glass it is based on given features.


## Data Dictionary for `MushroomDataset.csv`
- **type: edible=e, poisonous=p** (this is the class label your classifier should predict)
- cap-shape: bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s
- cap-surface: fibrous=f,grooves=g,scaly=y,smooth=s
- cap-color: brown=n,buff=b,cinnamon=c,gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y
- bruises: bruises=t,no=f
- odor: almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s
- gill-attachment: attached=a,descending=d,free=f,notched=n
- gill-spacing: close=c,crowded=w,distant=d
- gill-size: broad=b,narrow=n
- gill-color: black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y
- stalk-shape: enlarging=e,tapering=t
- stalk-root: bulbous=b,club=c,cup=u,equal=e,rhizomorphs=z,rooted=r,missing=?
- stalk-surface-above-ring: fibrous=f,scaly=y,silky=k,smooth=s
- stalk-surface-below-ring: fibrous=f,scaly=y,silky=k,smooth=s
- stalk-color-above-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
- stalk-color-below-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
- veil-type: partial=p,universal=u
- veil-color: brown=n,orange=o,white=w,yellow=y
- ring-number: none=n,one=o,two=t
- ring-type: cobwebby=c,evanescent=e,flaring=f,large=l,none=n,pendant=p,sheathing=s,zone=z
- spore-print-color: black=k,brown=n,buff=b,chocolate=h,green=r,orange=o,purple=u,white=w,yellow=y
- population: abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y
- habitat: grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d

## Data Dictionary for `GlassDataset.csv`

The class labels are under 'Type' column. Here's what the number in that column means:
- 1: Glass used in windows
- 2: Glass not used in windows

The features are as follows:
1. Refractive Index of the glass

Weight percentage in the corresponding oxide for the following elements:
2. Sodium
3. Magnesium
4. Aluminum
5. Silicon
6. Potassium
7. Calcium

## Result and code

Please see code [here](https://github.com/mingge612/KNN/blob/main/KNN.ipynb) for details.

