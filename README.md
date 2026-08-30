📊 Sales Data Analysis (EDA) — Superstore Dataset

Bu layihə satış (sales) datasetinin ətraflı Exploratory Data Analysis (EDA) işidir. Layihə çərçivəsində məlumatlar təmizlənmiş, statistik təhlil edilmiş və biznes qərarlarına dəstək olacaq insight-lar çıxarılmışdır.

🗂 Dataset
Fayl: analiznew.csv
Əsas sütunlar: Order Date, Sales, Profit, Discount, Quantity, Customer ID, Segment, Region, City, Category, Sub-Category, Product Name, Ship Mode
🛠 İstifadə olunan alətlər
Python: pandas, numpy, matplotlib, seaborn, scipy.stats
Mühit: Google Colab / Jupyter Notebook
🔍 Görülən işlər
1. Data Cleaning & Feature Engineering
Boş (null) dəyərlərin aşkarlanması və silinməsi
Order Date sütununun datetime formatına çevrilməsi
Year, Month və Profit Margin kimi yeni sütunların yaradılması
2. Outlier Analizi
Sales və Profit üzrə IQR metodu ilə outlier-lərin aşkarlanması
Outlier-siz datasetdə profit paylanmasının histogram vasitəsilə vizuallaşdırılması
3. Statistik Təhlil
Mean, median, mode və standart sapma hesablanması
Q-Q plot vasitəsilə Profit və Sales-in normal paylanmaya uyğunluğunun yoxlanması (nəticə: sağa əyilmə və outlier-lər mövcuddur)
Dəyişənlər arasında korrelyasiya (heatmap)
4. Qruplaşdırma və Aqreqasiya
Müştəri, Segment, Region, City, Category, Sub-Category və Product Name üzrə Sales/Profit/Quantity analizi
Zərərli (mənfi profit gətirən) sub-category və məhsulların müəyyənləşdirilməsi (Bookcases, Tables, Supplies)
Endirimlərin (Discount) profit itkisi ilə əlaqəsinin araşdırılması
Ship Mode üzrə effektivlik müqayisəsi
5. Vizuallaşdırma
Bar plot, box plot, heatmap, line plot, scatter plot və pie chart-larla:
Segment/Region/Category üzrə Sales və Profit
Aylıq Sales & Profit trendi
Top 5 Sub-Category üzrə aylıq satış artımı
Top 5 şəhər və sub-category üzrə profit
Sub-Category üzrə Profit Margin müqayisəsi
💡 Əsas Nəticələr (Key Insights)
Standard Class çatdırılma üsulu ən çox istifadə olunan və ən sərfəli seçimdir; First Class və Same Day daha az istifadə olunur və nisbətən aşağı profit gətirir.
Bookcases, Tables və Supplies sub-category-ləri ümumilikdə şirkətə zərər gətirir; xüsusilə yüksək endirimlərlə satılan Binders məhsulları yüksək satışa baxmayaraq mənfi profit göstərir. Bununla belə, bu sub-category-lərin daxilində həm zərər verən, həm də xeyir gətirən məhsullar mövcuddur — yəni zərər bütün məhsullara deyil, konkret məhsul adlarına aiddir.
Profit və Sales dəyişənləri normal paylanmaya uyğun deyil — sağa əyilmə və yüksək outlier-lər mövcuddur.
Ən çox profit gətirən şəhərlər və müştərilər müəyyənləşdirilib, bu da hədəflənmiş marketinq strategiyaları üçün istifadə oluna bilər.
📊 Əlavə fayllar

Bu Python/Jupyter analizindən əlavə, eyni dataset üzərində Excel və Power BI faylları da hazırlanmışdır (dashboard və hesabatlar üçün).
Author: Səkinə Əliyeva – Aspiring Data Analyst
Email: aliyevaa.sakina@gmail.com
