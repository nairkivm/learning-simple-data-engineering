- Feature Engineering: membuat fitur baru/modifikasi fitur yang sudah ada
    - Example: 
        - Label encoding : membuat label pada dataset 
        - One hot encoding : setiap kategori di label ya/tidak
        - Binning : pembuatan kategori untuk dataset dengan rentang tertentu
    - Feature Extraction : bisa dengan apply()
    - Encoding:
        - astype('category')
        - .cat.codes -> generate label encoding (data kategorikal -> numerikal)
        - One hot encoding : pd.get_dummies(dataframe, columns=["nama_kolom"])
    - Binning:
        - Custom binning : pd.cut(dataframe['nama_kolom'], bins = <rentang_nilai> labels = <data_label>)
            - rentang nilai : list [x, y, z] -> (x, y], (y, z]
    - Feature Interaction
        - interaksi antarkolom di dataframe
