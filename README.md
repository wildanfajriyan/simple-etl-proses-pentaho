# **simple etl playstore dataset**

CSV from [Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps?select=googleplaystore.csv)

## etl proses

![](screenshot/etl-proses.png)

### CSV file input

![](screenshot/import-csv.png)

```
importing googleplaystore.csv
```

![](screenshot/csv-file.png)

### Sort rows

![](screenshot/sort-rows.png)

```
sorting field App secara Ascending
```

#### Sort rows result

![](screenshot/sort-rows-result.png)

### Filter rows

![](screenshot/filter-rows.png)

```
menghapus data baris 1 - 7
```

#### Filter rows result

![](screenshot/filter-rows-result.png)

### Unique rows

![](screenshot/unique-rows.png)

```
menghapus data duplikat pada field App
```

#### Unique rows result

![](screenshot/unique-rows-result.png)

### Select values

![](screenshot/selected-values-remove.png)

```
menghapus field yang tidak diperlukan
```

#### Before remove field

![](screenshot/selected-values-remove-before.png)

#### After remove field

![](screenshot/selected-values-remove-after.png)

### Replace in string

![](screenshot/replace-string.png)

```
Field Rating jika ada value yang nilai nya NaN maka ganti menjadi 0
Field Size cari kata berakhir M ganti dengan " MB" dan juga k ganti dengan " k
```

#### Replace in string result

![](screenshot/replace-string-result.png)

### Select values

![](screenshot/selected-values-lowercase.png)

```
Semua Fieldname dirubah menjadi lowercase
```

#### Select values result

![](screenshot/selected-values-lowercase-result.png)

### JSON output

![](screenshot/json-output.png)

```
Load data CSV kedalam format JSON
```

#### JSON output result

![](screenshot/json-output-result.png)
