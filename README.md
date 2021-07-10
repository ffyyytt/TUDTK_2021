# TUDTK_2021
Chuẩn bị: ta tải các bộ dataset về máy và đặt vào thư mục datasets

- Tải *owid-covid-data.csv* từ [Total COVID-19 Tests Performed by Country](https://data.humdata.org/dataset/c87c4508-9caf-4959-bf06-6ab4855d84c6)

- Tải *can_covid19.csv* từ [Coronavirus disease (COVID-19): Outbreak update](https://www.canada.ca/en/public-health/services/diseases/2019-novel-coronavirus-infection.html#a1)

- Tải *reported_flights_stats.csv* từ [Domestic and international Itinerant movements](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=2310000801)

- Tải *canada_population_by_prov.csv* từ [Population estimates, quarterly](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1710000901)

- Tải *covid/time_series_covid19_confirmed_global.csv; covid/time_series_covid19_deaths_global.csv; covid/time_series_covid19_recovered_global.csv* từ [Novel Coronavirus (COVID-19) Cases Data](https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases)

- Tải *covid/covid19-canada.csv* từ [COVID-19 daily epidemiology update](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html)

Để lấy dữ liệu về các chuyến bay ta chạy notebook *crawl_data.ipynb*.

Tiếp theo ta chạy *process_positive_rate_world.ipynb* để tính tỷ lệ dương tính các quốc gia trên thế giới.

Ta chạy *process_positive_rate_can.ipynb* để tính tỷ lệ dương tính ở các ban của Canada.

Ta chạy *interpolate_positive_rate.ipynb* để tính tỷ lệ dương tính mỗi lần kiểm tra.

Chạy *flight-seir-Canada.ipynb* để lưu trữ lại dữ liệu cho các lần xử lý sau.

Để chạy mô hình ta chạy *early_time_prediction.ipynb* và *reopen_simulation.ipynb*
