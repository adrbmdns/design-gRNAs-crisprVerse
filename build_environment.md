## 1. Create a conda environment with R 

```sh
conda create -n crisprVerse r-essentials r-base # -n:name 
```

## 2. Activate conda environment 

```sh
conda activate crisprVerse 
```

## 3. Install devtools 

```sh
conda install -c conda-forge r-devtools
```

## 4. Open R

```sh
R
```

## 5. Install BiocManager 

```R
install.packages("BiocManager")
```

## 6. Install crisprVerse 

```R
BiocManager::install("crisprVerse") 
```

## 7. Install crisprDesignData 

```R
devtools::install_github("crisprVerse/crisprDesignData") 
```

## 8. Install crisprBwa 

```R
BiocManager::install("crisprBwa") 
```