# PREDICTIVE_ANALYTICS_KNIME_PYTHON_ENTEGRATION
Bu proje, machine learning modellerinin knime ve python entegrasyonu kullanılarak uygulanmasını içerir.

Knime analytics platform'da python extension kullanılarak aşağıda belirtilen tüm preprocessing işlemlerinin python'da yapılarak knime'a entegre edillmesi.

- belirli kolonların silinmesi
- missing value'ları9n bu8lunması
- nan odometer değerleri için mean değerlerini hesaplayan fonksiyon
- calc_nanvalues_mean_func fonksiyonunun her bir satır için çalıştırılması 
- outlier'ların bulunup gerekli işlemlerin yapılması
- type conversion
- one hot encoding

Belirtilen tüm machine learning adımlarının knime'da uygulanması ve modellerin değerlendirilmesi
- data frame concatenation
- rule based ro0w filpter
- column filter
- normalization,
- Linear regression
- random forest regression
- gradient boosted trees regression
- artificial neural networks  

Knime'da aşağıdakilerin uygulanması gereklidir.
- Excel Reader node'larının konfigurasyonlarının, verilerin dosya isimleri dikkate alınarak(part1, part2...) güncellenmesi.
Veriler aşağıdaki linkten alınabilir:

- Python environment konfigurasyonunun Knime'da (File -> Preferences -> knime -> python) konfigure edilmesi gereklidir.
Knime 
- python exception'ın eklenmesi. (File -> Install knime extensions) 
